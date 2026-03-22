# Interview Transcript: Dr. Michael Chen
**Date:** October 18, 2025
**Interviewer:** David (PM)
**Duration:** 52 minutes
**Course:** Data Structures (CS 201), 150 students, 4 TAs

---

*[Recording starts, sounds like professor's office, door closing]*

**David:** Thanks for making time, I know you're busy.

**Dr. Chen:** Yeah no problem. I actually have a lot of thoughts on this so you might have to cut me off.

**David:** Ha, no that's great. I want to hear everything.

**Dr. Chen:** Okay so, background: I've been teaching Data Structures for eight years. Before GradeFlow I was using Gradescope, which is actually pretty good for CS specifically because of the auto-grading stuff. But I switched because - well actually, can I go on a tangent about why I switched?

**David:** Please.

**Dr. Chen:** So Gradescope is great for the technical grading. Like, run the code, does it pass the test cases, done. But my issue was I had no idea what my TAs were doing. Like zero visibility. They'd grade the style portions and the partial credit stuff and I'd just have to trust them. And then at the end of semester I'd look at grade distributions and be like "wait, why does one TA's stack have an average of 78 and another's have an average of 85?"

**David:** So you came to GradeFlow for the TA management?

**Dr. Chen:** That's what sold me. The marketing was all "manage your TAs better, see what they're doing, etc etc." And I mean, it's better than Gradescope for that. But I still feel like I'm flying blind half the time.

**David:** Can you give me a specific example?

**Dr. Chen:** Oh yeah, let me tell you about last semester. So I have this TA - James - first year PhD student, really smart guy, knows the material cold. But he was drowning. Like, completely underwater. And I didn't know until week ten when students started emailing me asking where their grades were.

**David:** How far behind was he?

**Dr. Chen:** Sixty hours. Sixty hours behind on grading. That's like three full assignments that hundreds of students were waiting on.

**David:** How did that happen without you noticing?

**Dr. Chen:** That's my point! GradeFlow shows me the grades that have been entered, but it doesn't like... tell me when something's wrong? There's no alert. No notification. No "hey, James usually finishes by Wednesday and it's now Friday and he hasn't started." I only noticed because students complained.

**David:** So you need earlier warning.

**Dr. Chen:** Yes. Like, massively earlier. I should have known in week four or five that James was slipping behind. At that point it's recoverable. By week ten it's a crisis.

*[sound of chair creaking]*

**Dr. Chen:** And here's the thing about James specifically - he was too embarrassed to tell me. He thought he could catch up. He thought asking for help would make him look incompetent. And I get that, I really do - he's a first year PhD student trying to prove himself. But we could have avoided this whole mess if I'd had visibility earlier.

**David:** What would that look like?

**Dr. Chen:** I don't know exactly. Maybe like a status dashboard? Where I can see at a glance - here's how much grading each TA has done, here's how much is left, here's whether they're on track. Traffic light style almost. Green means fine, yellow means starting to slip, red means we have a problem.

**David:** That makes sense. What about the consistency issue - you mentioned grade distributions varying.

**Dr. Chen:** Oh god yes. So in CS, partial credit is everything. Our assignments aren't like English essays where you're evaluating arguments. It's like: did the code work? If yes, full points. If no, how wrong was it and why?

**David:** That sounds more objective at least?

**Dr. Chen:** You'd think! But here's the thing. A student might write code that's like 90% correct. It does most of what it's supposed to do but has a bug in one edge case. One TA might say "well it mostly works, 8/10." Another TA might say "it fails the test case for edge case X, 5/10." Same submission. Same rubric. Three point difference.

**David:** Wow.

**Dr. Chen:** And the rubric says - this is a direct quote - "partial credit for partially correct solutions." What does that mean? What does "partially correct" mean? It's a judgment call. And I have four TAs making that judgment call differently on every single submission.

**David:** How do you handle that currently?

**Dr. Chen:** Sunday nights. I spend my Sunday nights spot-checking grades. I literally pull random samples from each TA and compare. "Did they grade this consistently? Does this score make sense?" And sometimes I find problems and then I have to message the TA and be like "hey, can you look at this again?" And sometimes they push back and say they think their grade was right and then I have to arbitrate and...

*[sighs]*

**Dr. Chen:** It's exhausting. That's not a sustainable system.

**David:** How long do you spend on that?

**Dr. Chen:** Two, three hours? Sometimes more if I find something weird. And that's just spot-checking - I'm not looking at everything. I'm sampling like 5% of grades. Who knows what I'm missing in the other 95%.

**David:** What would be better?

**Dr. Chen:** Automated flagging. Like, if GradeFlow could just tell me "hey, TA X's grades on this assignment are statistically different from TA Y's grades." Not in a punitive way, just as information. Then I could investigate. Did TA X misunderstand the rubric? Is TA Y being too lenient? Maybe they're both fine and it's just noise. But at least I'd know to look.

**David:** So the system should surface anomalies.

**Dr. Chen:** Exactly. Right now I have to go looking for problems. I want problems to come to me. With enough context that I can actually do something about them.

*[pause, typing sounds]*

**Dr. Chen:** Actually can I show you something? I have a spreadsheet I made myself.

**David:** Sure.

**Dr. Chen:** Okay so this is... ugly, but it works. I export all the grades from GradeFlow and then I run some formulas. Here's average by TA, here's standard deviation by TA, here's a chart showing grade distributions. See how TA 2 is like a full 8% higher than everyone else?

**David:** Yeah that's pretty stark.

**Dr. Chen:** Right. And this took me like four hours to build and I have to manually update it every week. This should just... be a feature. In the product. That updates automatically. I shouldn't have to become an Excel expert to manage my TAs.

**David:** Completely fair.

**Dr. Chen:** And here's the other thing - what do I do with this information? Like okay, I know TA 2 is grading easier. Now what? I can go talk to her and say "your grades are higher than everyone else" but that's kind of accusatory? And maybe she'll say "yeah because everyone else is too harsh" and then we're in an argument about philosophy of grading.

**David:** What would be more helpful?

**Dr. Chen:** I think... side by side comparison? Like, show me the same submission graded by two different TAs. Not to call anyone out but so we can discuss as a team. "Here's how TA 2 graded this, here's how TA 3 graded the same thing, let's talk about the difference." Make it a calibration exercise instead of a criticism.

**David:** That's a good framing.

**Dr. Chen:** Because my TAs aren't trying to be inconsistent. They all want to do a good job. They just don't have visibility into how their grading compares. They're all grading in isolation and assuming they're doing it right.

*[pause]*

**Dr. Chen:** You know what I wish? I wish grading was a team sport instead of individual assignments. Like what if all my TAs could see each other's work - anonymized or whatever - and naturally calibrate just by osmosis? Instead of me having to be the central point of quality control.

**David:** Interesting. Like peer calibration.

**Dr. Chen:** Yeah exactly. Take me out of the equation. Let the TAs calibrate each other. I'd still want visibility into the overall patterns, but the day-to-day consistency could be a distributed thing.

**David:** Let me ask about something else - you mentioned James was struggling but didn't want to ask for help. Is that common?

**Dr. Chen:** I think so? Especially for first-year PhD students. They're trying to prove themselves. They don't want to seem like they can't handle it. And honestly the culture in academia is kind of... sink or swim? Like nobody sat me down when I was a TA and said "here's how to manage your time, here's when to ask for help." You just figure it out.

**David:** Does GradeFlow make that easier or harder?

**Dr. Chen:** Hmm. Neutral I guess? Like it doesn't make it worse. But it also doesn't... I don't know, create psychological safety? Is that the term? There's no way for a TA to flag that they're struggling without it feeling like admitting failure.

**David:** What would that look like if it existed?

**Dr. Chen:** Maybe like... a private check-in? Something that asks how you're doing, not in a surveillance way but in a supportive way. And if someone says they're behind, maybe it automatically offers help or redistributes work instead of waiting for me to notice and intervene.

**David:** That's interesting.

**Dr. Chen:** Because right now the incentive for a struggling TA is to hide it as long as possible and hope they can catch up. That's the worst possible incentive structure. The incentive should be to flag early so we can address it.

*[phone buzzes]*

**Dr. Chen:** Sorry, one sec... okay that's fine. Where were we?

**David:** You were talking about incentives for flagging struggles early.

**Dr. Chen:** Right. Yeah. I guess the summary is - the grading tools in GradeFlow are solid. Like genuinely good. It's the people management layer that needs work. I need to see what's happening with my TAs before things become crises. Both for workload and for consistency.

**David:** If you had to prioritize one?

**Dr. Chen:** Workload visibility. Because inconsistency I can sort of fix retrospectively - adjust grades, do calibration, whatever. But when a TA falls 60 hours behind, that's irrecoverable. Those students waited ten weeks for grades. That's a failure. And I don't want that on my conscience.

**David:** Thank you, this has been really valuable.

**Dr. Chen:** Of course. And seriously, if you can build what I'm describing - early warning for workload, automated flagging for consistency - I would be your biggest advocate. I'd tell every professor I know.

**David:** That's great to hear.

**Dr. Chen:** Because I love GradeFlow overall. I really do. I'm not going back to Gradescope. I just need that next level of support for managing the humans in the system.

*[recording ends]*
