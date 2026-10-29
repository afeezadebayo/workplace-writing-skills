---
name: sops-process-docs
description: "Write SOPs, checklists, how-to guides, runbooks and handovers people actually follow: capturing the process from the expert, purpose, scope and roles, numbered one-action steps with exact system names, checks, warnings and exception tables, a newcomer test and an owner, version and review date. Use whenever someone needs an SOP, standard operating procedure, process document, checklist, how-to guide, runbook, handover document or wants to document how a task is done."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/workplace-writing/sops-process-docs/
  category: productivity
  subcategory: workplace-writing
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# SOPs and Process Documents

Standard operating procedures (SOPs) are meant to make work repeatable, but many are never used. They are written once by the person who knows the process best, full of assumed knowledge, long paragraphs and out-of-date screenshots, then stored where nobody can find them. When the expert leaves, the process breaks. Good process documents are short, step-by-step, tested by someone new and kept current.

This skill writes SOPs, checklists, how-to guides, runbooks and handover documents: it captures the process from the person who does it, defines purpose, scope and roles, writes numbered steps with one action each, adds checks, warnings and examples, tests the document with someone unfamiliar and sets an owner and review date.

## Operating principles
1. **One action per step.** Numbered, starting with a verb.
2. **Written for a capable newcomer.** Assume skill but not context.
3. **Tested by someone who has not done it.** Gaps show up when a newcomer follows it.
4. **Short and findable.** Link details; store where people work.
5. **Owned and reviewed.** Every document has an owner and a review date.

## Document types
| Type | Use | Format |
|---|---|---|
| SOP | Repeated process with standards to meet | Purpose, scope, roles, numbered steps, checks |
| Checklist | Routine task where steps are known | Short tick list |
| How-to guide | Task done occasionally | Steps with screenshots or examples |
| Runbook | Technical or incident response | Triggers, steps, escalation, rollback |
| Handover | Passing work to someone else | Status, contacts, open issues, where things are |
| Decision tree | Process with branches | If-then flow or table |

## When to use, and when not to
Use it for onboarding tasks, finance and admin processes, customer support procedures, operations, compliance steps, incident response and handovers.

Don't use it for policies that set rules rather than steps (`policies-guidelines`) or for one-off project plans (the Planning and Task Management `project-breakdown` skill).

## Inputs
- The process and its purpose.
- The person who does it now (interview, screen recording or notes).
- Tools, systems and access needed.
- Quality standards, deadlines and compliance rules.
- Where the document will live.

## Workflow

### Step 1. Capture the process
Interview the expert or record them doing the task, narrating each step. Note decisions, exceptions and common mistakes.

### Step 2. Define purpose and scope
What the process achieves, when it starts and ends, and what is out of scope.

### Step 3. Name roles
Who does each part, who approves and who to ask for help.

### Step 4. Write the steps
Numbered, one action each, verb first, with the system, field or button named exactly. Group into sections if longer than 15 steps.

### Step 5. Add checks and warnings
What good looks like after key steps; warnings before risky actions; examples of correct inputs.

### Step 6. Handle exceptions
Common problems and what to do, or a decision table for branches.

### Step 7. Test with a newcomer
Someone who has not done the task follows the document exactly; note every hesitation and question; fix them.

### Step 8. Publish and assign ownership
Store where people work, link from related tools, add owner, version and review date.

## SOP template
```
Title: <process name> | Owner: <name> | Version: <x> | Review: <date>
Purpose: <one sentence>
When to use: <trigger> | Time needed: <estimate>
Roles: <who does, who approves, who helps>
Before you start: <access, tools, information>
Steps
1. <Verb> <object> in <system>. Check: <what you should see>
2. ...
 Warning: <risk and how to avoid it>
If something goes wrong: <problem> -> <action> | Escalate to <name>
Related: <links>
Change log: <date, change, by>
```

## Writing steps
| Weak | Strong |
|---|---|
| The invoice should then be processed in the system. | 4. In Xero, open Bills, select the invoice and click Approve. |
| Make sure everything is correct. | 5. Check the amount matches the purchase order. If not, stop and email finance. |
| Upload it to the usual place. | 6. Save the PDF in Finance > Invoices > 2026 > October. |

## Checklist format
For routine tasks the team already knows, a checklist works better than a full SOP:
```
Month-end close checklist (owner: <name>)
[ ] Bank feeds reconciled
[ ] Supplier invoices approved
[ ] Payroll journal posted
[ ] Accruals reviewed
[ ] Report sent to finance director by day 5
```
Keep checklists to the steps people actually miss; long checklists get skipped.

## Handover document
```
Role or project: <name> | From: <name> | To: <name> | Date: <date>
Current status: <one paragraph>
Open tasks: <task, deadline, notes>
Key contacts: <name, role, what they help with>
Where things are: <folders, tools, passwords via the password manager>
Regular tasks: <what, when, link to SOP>
Risks and watch-outs: <list>
```

## Decision tables
| If | Then |
|---|---|
| Invoice under £1,000 and matches PO | Approve |
| Invoice over £1,000 | Send to finance director for approval |
| Invoice does not match PO | Return to supplier with reason |
Tables are easier to follow than nested paragraphs of conditions.

## Keeping documents current
Review each document on its date, after any process or tool change and after any mistake the document should have prevented. Record changes in the log. Archive documents that are no longer used so people do not follow old versions.

## Screenshots and videos
Use screenshots only where they prevent mistakes, such as which button to press on a crowded screen, and add a short arrow or highlight. A two-minute screen recording can sit alongside the written steps for visual learners, but the written steps remain the source of truth because they are easier to search and update.

Name each document after the task people search for, such as how to approve a supplier invoice.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Process varies by case | Use a decision table or separate short SOPs |
| Tools change often | Describe actions by name; refresh screenshots at review |
| Regulated process | Include required checks, approvals and records |
| Expert is leaving soon | Prioritise recording and a handover document now |
| Very long process | Split into linked SOPs by stage |
| Nobody follows the SOP | Ask why; shorten to a checklist; place it where work happens |

## Handoffs to related skills
- Staged writing: `writing-process`
- Plain language: `plain-english`
- Rules and standards: `policies-guidelines`
- Team style: `team-style-guide`
- Product help content: the Product-Led Growth `product-education` skill

## Worked example
A finance assistant was the only person who knew month-end invoice processing. The skill captured a recorded walkthrough, then wrote a 22-step SOP in three sections with exact screen names, checks after key steps, two warnings and a table of five common problems. A new team member followed it without help and hesitated at four points, which were rewritten. The SOP was linked from the finance channel with an owner and quarterly review date. When the assistant went on leave, month-end was completed on time by the new team member.

## Common mistakes
- Paragraphs instead of numbered steps.
- Assumed knowledge ("the usual place").
- Never testing with a newcomer.
- No owner or review date.
- Stored where nobody looks.

## Using an AI agent
The agent can turn a screen recording transcript or rough notes into numbered steps, flag vague steps, write checks and warnings, build exception tables and run a simulated newcomer test by asking what each step assumes. The process owner confirms accuracy.

## Self-check before you answer
- Is every step one action starting with a verb?
- Are checks, warnings and exceptions included?
- Was it tested by someone new?
- Does it have an owner, version and review date?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/workplace-writing/sops-process-docs/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
