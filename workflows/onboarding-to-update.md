# Onboarding to Update Workflow

This workflow takes you from "messy inbox of files" to "polished stakeholder updates" in one run.

## What it does

1. **Synthesize** - Read company overview and research files, extract key insights
2. **Summarize** - Create a learning summary combining what you found
3. **Format** - Put it into the company 1-pager template
4. **Humanize** - Apply writing style guidelines so it doesn't sound like AI
5. **Distribute** - Create versions for Slack, email, and wiki

## Instructions

Run this workflow when you need to quickly get up to speed on a topic and share what you learned.

---

## Step 1: Synthesize the Research

Read all files in `@research/` and identify the top 3-5 pain points or themes across the interviews. Save this as `user-research-synthesis.md`.

## Step 2: Create Learning Summary

Based on `@company-overview.md` and `@user-research-synthesis.md`, write a summary of key learnings. Focus on:
- What the company/product does
- Who the users are and what they struggle with
- What opportunities exist

Save as `learning-summary.md`.

## Step 3: Format as 1-Pager

Take `@learning-summary.md` and format it using the structure in `@templates/one-pager.md`.

Save as `one-pager-learning-summary.md`.

## Step 4: Humanize

Rewrite `@one-pager-learning-summary.md` using the guidelines in `@templates/writing-style.md`.

Make sure it sounds natural, not robotic. Remove corporate jargon. Keep it conversational but professional.

Update the file in place.

## Step 5: Create Distribution Versions

From `@one-pager-learning-summary.md`, create three versions:

1. **Slack message** - Use format from `@templates/slack-update.md`, save as `updates/slack-update.md`
2. **Email to manager** - Use format from `@templates/email-summary.md`, save as `updates/email-summary.md`
3. **Wiki page** - Use format from `@templates/company-wiki.md`, save as `updates/wiki-page.md`

---

## Customization

Each piece of this workflow can be modified:

- **Different research sources** - Point `@research/` at any folder of documents
- **Different templates** - Swap out the 1-pager, slack, email, wiki templates
- **Different style** - Update `writing-style.md` for your voice
- **Different outputs** - Add or remove distribution channels

## Running it

You can run this entire workflow with:

```
Run the workflow in @workflows/onboarding-to-update.md using the files in this folder
```

Or run individual steps by referencing specific sections.
