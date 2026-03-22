# Interview Transcript: Dr. Adaeze Okonkwo
**Date:** October 22, 2025
**Interviewer:** David (PM)
**Duration:** 44 minutes
**Course:** Organic Chemistry (CHEM 301), 180 students, 5 TAs

---

*[Recording starts, sounds like video call]*

**David:** Can you hear me okay?

**Dr. Okonkwo:** Yes, perfect. Let me just close this other window... okay. Ready.

**David:** Great. So tell me about your experience with GradeFlow, whatever comes to mind.

**Dr. Okonkwo:** Okay so I should preface this by saying I'm a very data-driven person. I have a chemistry background obviously so I think in terms of measurements and evidence. And what frustrates me about managing TAs is that I have all this... intuition? Feelings? But no data.

**David:** What do you mean?

**Dr. Okonkwo:** Like, I can sense that something's off with my TAs' grading. I'll look at the final grades for a problem set and think "this doesn't feel right." But I can't point to anything specific. It's like - you know when you run an experiment and the results look weird but you can't explain why? That feeling.

**David:** And you want more data to diagnose the issue.

**Dr. Okonkwo:** Exactly. I want to be able to say "TA X's grades are 12% higher than the mean and that's statistically significant at p < 0.05." I want to run analysis on my TAs' grading patterns the same way I'd run analysis on experimental results.

**David:** Can you do that with GradeFlow currently?

**Dr. Okonkwo:** Not really? I mean, I can export data and do my own analysis. Which I have done. Actually, let me tell you what I found.

**David:** Please.

**Dr. Okonkwo:** So last semester I pulled all the grades for my problem sets - all five TAs, all 12 problem sets - and I ran some basic stats. Average grade by TA, standard deviation, all that. And what I found was... kind of shocking honestly.

**David:** What did you find?

**Dr. Okonkwo:** My TAs' average grades ranged from 72% to 89%. Seventeen percentage points! On the same assignments, with the same rubric, with the same students. That's not noise. That's systematic bias.

**David:** Wow.

**Dr. Okonkwo:** And here's the thing - I don't know which TA is right. Is the 72% TA too harsh? Is the 89% TA too lenient? Maybe they're both wrong and the correct average is 80%. I have no way to tell. I don't have ground truth.

**David:** How did you handle that?

**Dr. Okonkwo:** Honestly? I didn't. I mean, I had conversations with the outliers. Told the 72% TA "you might be grading too hard" and the 89% TA "you might be grading too easy." But that's kind of useless advice, right? What does "too hard" mean without examples? They both thought they were grading correctly.

**David:** So the conversation didn't change behavior.

**Dr. Okonkwo:** Not really. Maybe temporarily. But without ongoing monitoring, everyone drifts back to their natural tendencies. The harsh grader is harsh, the lenient grader is lenient. And I don't have time to do this statistical analysis every week.

**David:** What would you need to see in GradeFlow?

**Dr. Okonkwo:** I want a dashboard. Like, a real dashboard. Not just "here are the grades" but "here are the grades with analysis." Show me distributions by TA. Show me trends over time. Flag when someone is an outlier. Give me the statistics automatically instead of making me do it in Excel.

**David:** Would you want alerts?

**Dr. Okonkwo:** Yes! Definitely. Like, email me when a TA's grades deviate more than one standard deviation from the mean. Or when their grading time is unusually fast or slow. Just tell me when something's weird so I can investigate.

*[pause]*

**Dr. Okonkwo:** Actually, can I tell you about another problem?

**David:** Of course.

**Dr. Okonkwo:** So one of my TAs - she's wonderful, really dedicated, smart - she had a family emergency mid-semester. Her mom got sick and she had to go home for a week. And her grading fell behind, which is totally understandable. But she didn't tell me.

**David:** Why not?

**Dr. Okonkwo:** I think she was embarrassed? Or she thought she could catch up? Or she didn't want to burden me with her personal problems? I don't know. But by the time I found out - which was when students started asking where their grades were - she was three weeks behind and completely overwhelmed.

**David:** That's really hard.

**Dr. Okonkwo:** And I felt terrible! She was going through a family crisis and instead of supporting her, I was the clueless professor who didn't notice. If I'd known earlier, I could have redistributed her work, given her time off, something. But I was blind.

**David:** Is there a way to prevent that?

**Dr. Okonkwo:** I mean, ideally yes. Some kind of early warning system. Not surveillance - I don't want to spy on my TAs - but just... pattern recognition? Like if someone's grading output suddenly drops, flag it. Could be a technical issue, could be personal, could be whatever. But at least I'd know to check in.

**David:** What about the TA's perspective - would they want that?

**Dr. Okonkwo:** That's a good question. I think if it's framed as supportive rather than punitive, yes? Like, "we noticed you're behind, do you need help?" rather than "you're behind, explain yourself." There's a way to do this that feels caring instead of controlling.

**David:** I like that framing.

**Dr. Okonkwo:** Because the current system puts all the burden on the TA to self-report problems. And that requires vulnerability. It requires admitting you're struggling. Which is hard for anyone but especially for PhD students who are already stressed and anxious about their performance.

**David:** Right.

**Dr. Okonkwo:** So take the burden off them. Have the system notice and reach out. Even better, have the system automatically offer solutions. "We noticed you're behind, would you like to redistribute some assignments to your co-TAs?" Click yes, done. Nobody has to have an awkward conversation.

*[pause, typing sounds]*

**Dr. Okonkwo:** I'm thinking out loud here but... you know how GradeFlow has great analytics for students? Like I can see which students are struggling, who's falling behind, who might need intervention?

**David:** Yeah.

**Dr. Okonkwo:** I want that for TAs. Seriously. The same level of insight. Who's struggling? Who's falling behind? Who might need intervention? TAs are also learners in a way - they're learning how to teach. They deserve the same support we give students.

**David:** That's a really interesting parallel.

**Dr. Okonkwo:** Right? And I bet if you surveyed TAs, they'd want this too. Not to be watched, but to be supported. To get feedback on how they're doing. To know if they're grading correctly or not. Right now they're operating in a vacuum.

**David:** Let me ask about something specific - you mentioned rubrics. Are they helpful?

**Dr. Okonkwo:** Yes and no. So organic chemistry problems are pretty structured. Like, "balance this equation" or "draw the mechanism for this reaction." So you can have specific rubric criteria - "2 points for correct products, 1 point for showing electron movement," etc.

**David:** That sounds clear.

**Dr. Okonkwo:** But even then there's judgment. What about a student who got the right answer but skipped a step? What about a student who made a sign error but the logic was correct? These edge cases come up constantly and the rubric can't anticipate all of them. So TAs end up making judgment calls, and different TAs call them differently.

**David:** How do you handle those edge cases now?

**Dr. Okonkwo:** Slack mostly. We have a TA Slack channel and people post questions. "How should I grade this?" And then I or an experienced TA will weigh in. But it's reactive. Someone has to encounter the edge case and think to ask. And not everyone does.

**David:** What would be better?

**Dr. Okonkwo:** Some kind of evolving rubric that captures decisions as we make them? Like, the first time someone asks "how do I grade a sign error," we make a ruling and that becomes part of the rubric. A living document that gets smarter over time.

**David:** Oh that's interesting.

**Dr. Okonkwo:** Because right now the same question gets asked multiple times by different TAs in different semesters. We're not learning as an organization. Every semester we start from scratch.

*[pause]*

**Dr. Okonkwo:** Sorry, I'm rambling.

**David:** No this is great. Anything else you want to add?

**Dr. Okonkwo:** Just... I guess my overall feeling is that GradeFlow is a really good tool for the mechanical parts of grading. Uploading assignments, distributing to TAs, entering grades, all that. But the human parts - managing TAs, ensuring consistency, supporting people who are struggling - that's still mostly on me. And I don't have the tools or the time to do it well.

**David:** That's really helpful feedback.

**Dr. Okonkwo:** Happy to help. And listen, I'm a scientist - I know building these features isn't trivial. But if you can get there, you'll have a genuinely differentiated product. Everyone can build a grade book. Not everyone can build a TA support system.

**David:** Thank you so much, Dr. Okonkwo.

**Dr. Okonkwo:** Of course. Let me know if you need anything else.

*[recording ends]*
