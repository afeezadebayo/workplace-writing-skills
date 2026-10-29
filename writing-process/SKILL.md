---
name: writing-process
description: "Write any workplace document in stages: context and reader, a one or two-sentence key message, an outline agreed first, a fast draft from real sources, a fresh-reader test that finds gaps, editing for cuts and clarity and a final fact check, with shapes for memos, proposals, reports, briefs, SOPs, policies and updates. Use whenever someone needs to write a document, memo, proposal, report, brief, plan, policy or long update, is stuck on a draft, or wants help co-writing a document with an AI agent."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/workplace-writing/writing-process/
  category: productivity
  subcategory: workplace-writing
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Workplace Writing Process

Most workplace documents fail before the first sentence. The writer starts typing without knowing who will read it, what decision it should support or what the reader already knows, then edits for hours. AI makes drafting instant but often makes this worse: long, polished text that sounds confident and says little. Anthropic's own document co-authoring skill takes a staged approach: gather context, build structure, then test the draft with a fresh reader that has no background, to catch gaps before real readers do. [Reported, anthropics/skills doc-coauthoring]

This skill writes any workplace document in stages with the user: purpose and reader, key message, outline, draft, a fresh-reader test, edits and a final check. It works for memos, proposals, reports, briefs, process documents, policies and long emails, and hands off to specialist skills for each format.

## Operating principles
1. **Reader first.** Who reads it, what they know, what they need to do afterwards.
2. **Message before words.** Write the main point in one or two sentences before drafting.
3. **Structure before style.** Agree the outline before polishing sentences.
4. **Test with a fresh reader.** Someone (or an agent) without context finds the gaps.
5. **Shorter is usually better.** Cut anything the reader does not need to act.

## Stages
| Stage | Output | Time share |
|---|---|---|
| 1. Context | Purpose, reader, decision, constraints, sources | 15% |
| 2. Message | The main point in one or two sentences | 5% |
| 3. Outline | Headings with one-line summaries | 15% |
| 4. Draft | Full text, fast, without polishing | 30% |
| 5. Reader test | Questions and confusions from a fresh reader | 10% |
| 6. Edit | Fix gaps, cut, simplify, format | 20% |
| 7. Final check | Facts, names, numbers, links, tone | 5% |

## When to use, and when not to
Use it for any document longer than a short email: memos, proposals, reports, briefs, SOPs, policies, plans, case studies and announcements.

Don't use it for quick replies (the Email and Inbox skills) or marketing copy (the Content, Copy and PR skills).

## Inputs
- What the document is for and who asked for it.
- The readers and what they already know.
- Source material: notes, data, previous documents, conversations.
- Constraints: length, template, deadline, tone, approval process.

## Workflow

### Step 1. Gather context
Ask the questions that change the document: who reads it, what should they do or decide, what do they know, what worries them, what must be included, what is the deadline? Read the sources.

### Step 2. Write the key message
One or two sentences the reader should remember. If this is hard, the thinking is not finished; resolve it before drafting.

### Step 3. Outline
Headings with a one-line summary each, in the order the reader needs: usually conclusion and recommendation first, then reasons and evidence, then details. Agree the outline with the user.

### Step 4. Draft
Write section by section from the outline, using the user's sources and facts only. Mark gaps with clear placeholders.

### Step 5. Run the reader test
Give the draft, without background, to a fresh reader (a colleague or a separate agent session) and ask: What is this asking me to do? What is unclear? What questions do you have? What would you cut?

### Step 6. Edit
Fix every confusion the test found. Cut repetition, background the reader does not need and hedging. Simplify long sentences. Add headings, bullets or a table where they help scanning.

### Step 7. Final check
Facts against sources, names and titles, numbers and units, dates, links and attachments, consistent terms, tone and length.

## Document shapes
| Document | Lead with |
|---|---|
| Decision memo | The decision needed and recommendation |
| Proposal | The problem, the proposed solution and the cost |
| Report | Key findings and what they mean |
| Brief | Goal, audience, scope and deadline |
| SOP | Purpose, when to use it, steps |
| Policy | What the rule is, who it applies to, why |
| Update | What changed and what the reader needs to do |

## Reader test prompts
```
Read this document as <reader role> with no other context.
1. In one sentence, what is it asking you to do or decide?
2. Which parts were unclear or needed more information?
3. What questions would you ask the author?
4. What could be cut without losing anything you need?
```

## Output format
```
1. Context summary (reader, purpose, decision)
2. Key message
3. Outline (for approval)
4. Draft
5. Reader test findings
6. Edited version
7. Final check list
```

## Working with an AI agent
The agent is most useful when the user stays in charge of the thinking. Good division of work: the user supplies purpose, reader, sources and judgement; the agent asks context questions, proposes the key message and outline, drafts sections from the sources, runs the fresh-reader test in a separate session, suggests cuts and checks facts. The user approves the outline before drafting and reads the final version aloud before sending. Avoid asking for a finished document in one prompt; staged work produces shorter, clearer documents.

## Writing for decision makers
- Put the ask and recommendation in the first paragraph.
- Give options and trade-offs, not only the preferred answer.
- Show costs, risks and timing plainly.
- Keep the main document short; move detail to appendices.
- End with the next step and who owns it.

## Signs a document is ready
- A reader can say what it asks in one sentence.
- Every section helps the reader act or decide.
- Numbers match the sources.
- It reads naturally aloud, without stumbling over long sentences.
- It is shorter than the first draft.

## Version control
Keep one shared version of the document with comments rather than emailing copies. Note major changes and who approved them at the end, so readers know which version is final.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Very tight deadline | Short context, message, outline and draft; reader test on the summary only |
| Several audiences | Summary for executives first, details in sections or appendices |
| Sensitive content | Keep facts precise; limit distribution; review with the right people |
| User has a rough draft | Start at the reader test and edit stages |
| Required template | Fit the content to it; keep the message first where allowed |
| Missing information | Ask, or mark placeholders rather than inventing |

## Handoffs to related skills
- One-page memos: `memos-one-pagers`
- Proposals: `proposals`
- Reports: `reports`
- Process documents: `sops-process-docs`
- Executive summaries: `executive-summaries`
- Editing and plain English: `editing-tightening`, `plain-english`

## Worked example
A programme manager needed a document asking leadership to extend a pilot. Context showed the readers were three directors who had seen early results but not costs. The key message: "Extend the pilot by three months at a cost of £45,000, because it cut processing time by 30% and the full rollout decision needs winter data." The outline put the recommendation first, then results, cost, risks and next steps. A fresh-reader test asked what happens if the pilot is not extended, so a short "options" paragraph was added. The final document was two pages instead of the original six, and the extension was approved in one meeting.

## Common mistakes
- Drafting before knowing the reader and message.
- Background first, recommendation last.
- Polishing sentences in an outline that does not work.
- Skipping the fresh-reader test.
- Inventing facts to fill gaps.

## Self-check before you answer
- Is the reader and purpose clear?
- Can the key message be stated in two sentences?
- Did a fresh reader understand what to do?
- Were facts checked against sources?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/workplace-writing/writing-process/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
