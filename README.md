<!--
author:   ICoBC - International Council on Badges and Credentials
email:    info@icobc.net
version:  1.0.0
language: en
narrator: UK English Female
comment:  A practical course in which you turn a learning or work activity into a credential specification with a clear claim, criteria, evidence and portable metadata, and test it with a reader.

@style
:root { --icobc-navy:#02375B; --icobc-orange:#F78222; --icobc-cyan:#5DCAE7; --icobc-lime:#B1CF37; --icobc-mist:#F1F5F8; --icobc-line:#D8E2E9; --icobc-muted:#4F6576; }
body { font-family: "Open Sans", Arial, sans-serif; }
h1, h2, h3, h4 { color: var(--icobc-navy); }
a { color: var(--icobc-navy); }
table th { background: var(--icobc-mist); color: var(--icobc-navy); }
blockquote { border-left: 4px solid var(--icobc-orange); background: var(--icobc-mist); padding: 8px 16px; }
@end
-->

# Designing a Credential: Claim, Criteria, Evidence and Metadata

*Turn a learning or work activity into a credential that means something to a reader.*

## About this course

**Course ID:** ICB-P01 | **Framework alignment:** ICoBC Credentialing Skills Framework (ICSF), skill CRDS "Credential design" (VRITE pillar: Rigor), level L2 "Operate", stage A "Ability".

At this level you draft credential specifications from templates, including outcomes, criteria and required metadata. The Ability stage means you practise on realistic tasks in a controlled setting. In this course the setting is a set of cases and a project: you design one credential from start to finish.

**Who this course is for**

- L&D and corporate academy leads
- Programme and micro-credential leads
- Learning designers and teaching staff
- Professional bodies and sector associations

**Prerequisite:** ICB-F01 Digital Badges and Credentials Essentials.

**Learning outcomes.** After this course you can:

1. Write a credential claim and outcomes that state what the earner can do.
2. Define criteria and the evidence that proves each of them.
3. Complete the metadata needed for portability, including alignment, level and workload.
4. Test a specification with a reader outside the issuing team and revise it.

**Workload.** 10 hours notional learning in a blended cohort. This file covers the self-paced part. Live and workshop elements appear as facilitator notes.

**How it is assessed.** You submit a complete credential specification for a real or realistic credential. A person assesses it with the ICoBC design rubric, and a peer reviews it. A final knowledge check supports the assessment.

**Badge.** "Designing a Credential: Claim, Criteria, Evidence and Metadata (Ability, L2)", alignment code ICSF-CRDS-L2-A.

**Quality focus.** VRITE Rigor (criteria and evidence) and Value (meaning to readers).

| Outcome | Module | How it is assessed |
|---|---|---|
| 1. Write a credential claim and outcomes that state what the earner can do | Start from the claim; Outcomes and criteria | Module quizzes; specification, rubric rows 1 and 2; final knowledge check |
| 2. Define criteria and the evidence that proves each of them | Outcomes and criteria; Evidence that proves the claim | Module quizzes; specification, rubric rows 3 and 4; final knowledge check |
| 3. Complete the metadata needed for portability, including alignment, level and workload | Metadata for portability; Naming and description | Module quizzes; specification, rubric rows 5 and 6; final knowledge check |
| 4. Test a specification with a reader outside the issuing team and revise it | Testing with readers | Reader test notes and revision log; peer review; rubric row 7 |

**How the course works.** Each module has short units, one worked example, one practice activity and a quiz. Keep one working document open. Every practice activity adds a section to your credential specification, so by Module 6 you hold a full draft.

**Choose your credential.** Before you start, pick one real or realistic credential to design. Good choices are a short course in a college, a workplace skills programme in a corporate academy, a professional body's practice award, or a project-based micro-credential. Choose something you know well enough to describe in detail.

<details>
<summary>Facilitator notes</summary>

**Kick-off session (about 60 minutes, live).** Ask each participant to present their chosen credential in two minutes: who earns it, who reads it, and what decision a reader might make with it. Form peer review pairs now, so each pair works together through Module 6. Check that no participant has chosen a credential that is too broad (for example "leadership") to specify in the time available.

**Materials.** Participants need a copy of the specification template (see Module 1) and access to the rubric in "Assessment and badge".
</details>

## Start from the claim

### Why a credential needs a claim

A credential is a statement about a person. The issuer says: this earner can do this, and here is how we know. The first half of that sentence is the claim. Everything else in the specification exists to support it.

Many credentials begin with an activity: a course, a workshop, a project, a shift rotation. The activity tells a reader what the earner attended or completed. A claim tells the reader what the earner can do afterwards. Readers such as employers, admissions teams and professional bodies make decisions on the second kind of information.

Start your design from the claim, then work backwards to the activity. That order protects you from a common problem: a credential that lists topics covered and leaves the reader to guess the capability.

{{1}}
<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Funnel from activity to claim to criteria to evidence</title>
  <desc>A funnel with four stages from top to bottom: learning or work activity, credential claim, criteria, and evidence. The funnel narrows as the specification becomes more precise.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="100" y="30" width="600" height="70" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="62" text-anchor="middle" font-size="18" fill="#02375B" font-weight="bold">1. Activity</text>
  <text x="400" y="86" text-anchor="middle" font-size="14" fill="#4F6576">What people do: course, project, work task</text>
  <rect x="160" y="120" width="480" height="70" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="152" text-anchor="middle" font-size="18" fill="#02375B" font-weight="bold">2. Claim</text>
  <text x="400" y="176" text-anchor="middle" font-size="14" fill="#02375B">What the earner can do afterwards</text>
  <rect x="220" y="210" width="360" height="70" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="242" text-anchor="middle" font-size="18" fill="#02375B" font-weight="bold">3. Criteria</text>
  <text x="400" y="266" text-anchor="middle" font-size="14" fill="#02375B">What must be true to award it</text>
  <rect x="280" y="300" width="240" height="70" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="332" text-anchor="middle" font-size="18" fill="#02375B" font-weight="bold">4. Evidence</text>
  <text x="400" y="356" text-anchor="middle" font-size="14" fill="#02375B">What proves each criterion</text>
  <text x="400" y="410" text-anchor="middle" font-size="14" fill="#4F6576">Each stage is more precise than the one above it.</text>
</svg>

### The parts of a claim

A good claim has four parts. You can check any draft against them.

1. **An earner.** Who the statement is about. Usually "the earner".
2. **An action verb.** A capability a reader can picture, such as "plan", "calculate", "facilitate" or "review".
3. **An object.** What the action applies to, such as "a project budget" or "a customer complaint".
4. **A context or standard.** The conditions or quality level, such as "for a team of up to ten" or "following the organisation's data protection policy".

Compare two drafts for the same credential:

- Weak: "Understands project management."
- Stronger: "Plans a small project with a scope statement, a schedule and a risk register, and reports progress to a sponsor."

The weak draft uses "understands", which a reader cannot observe. The stronger draft names things the earner produces and does. You can check them against evidence later.

Avoid verbs such as "know", "understand", "appreciate" and "be aware of" in a claim. They describe an inner state. If awareness is the real aim, ask what the earner does differently because of it, and claim that.

### Who reads the claim

A credential has at least three kinds of reader: the earner, a reader who decides something based on it (an employer, a selector, a regulator), and the issuer's own team. Decide who the primary reader is before you write. A claim for a hiring manager reads differently from a claim for an internal audit team.

Write down this reader context in one line:

> The primary reader is a [role] who needs to decide [decision] and has [time or knowledge limit].

For example: "The primary reader is a site supervisor who needs to decide whether a new hire may operate a pallet truck unsupervised, and has two minutes to read the credential."

Keep that line next to your draft. In Module 6 you test it with a real reader.

**Worked example: Two claims from one activity**

*University or training provider.* A training provider runs a two-day workshop on writing grant proposals for community organisations. The original description reads: "Covers funding sources, proposal structure and budgeting." The designer rewrites it as a claim: "Writes a grant proposal of up to ten pages that states need, activities, outcomes and a budget, and submits it against a funder's published guidelines." The primary reader is a charity manager deciding whom to ask to lead an application.

*Corporate academy.* An HR department runs a programme for new team leaders. The original description reads: "Introduction to feedback conversations." The designer's claim: "Prepares and holds a structured performance feedback conversation with a team member, and records agreed actions in the HR system within two working days." The primary reader is a department head deciding which team leaders may run appraisals alone.

In both cases the activity stays the same. Only the statement changes, and the reader can now picture what the earner does.

**Practice activity: Draft your claim**

Open your specification template and write section 1. Do the following:

1. Write the reader context line for your chosen credential.
2. Draft one claim sentence with an action verb, an object and a context or standard.
3. Check it against the four parts. Underline each part in your draft.
4. Rewrite the claim if it uses "understand", "know" or "be aware of".

Keep your draft to one or two sentences. Illustrative template headings for your specification: 1 Claim, 2 Outcomes, 3 Criteria, 4 Evidence, 5 Metadata, 6 Name and description, 7 Reader test log.

<details>
<summary>Facilitator notes</summary>

**Workshop option (45 minutes).** In groups of three, each person reads their claim aloud. The others say what they picture the earner doing. If the picture differs from the author's intention, the claim needs work. Collect weak verbs on a shared list.

**Common problem.** Participants write a claim that restates the course title. Ask: "What can the earner do on Monday that they could not do last week?"
</details>

### Check your understanding

**Question 1.** Which claim states what the earner can do?

[( )] Understands the principles of customer service.
[( )] Attended a three-hour workshop on customer service.
[(X)] Resolves a customer complaint by listening, confirming the issue, offering a solution within policy and recording the outcome.
[( )] Is aware of the importance of good customer service.
[[?]] Look for an observable action with an object and a standard.
****
The third option names an action, an object and a standard. The other options describe an inner state or attendance, which a reader cannot check against observable behaviour.
****

**Question 2.** What is the main reason to start a credential design from the claim?

[( )] It makes the badge image easier to draw.
[(X)] The claim is the statement readers rely on, and criteria and evidence can then be built to support it.
[( )] It allows you to skip writing criteria.
[( )] It guarantees the credential will be accepted by every employer.
[[?]] Think about what readers use to make decisions.
****
The claim is what a reader relies on. Starting there lets you build criteria and evidence that support it. A claim does not remove the need for criteria and cannot guarantee acceptance.
****

**Question 3.** A designer writes: "Knows how to run a safe laboratory session." What is the best next step?

[( )] Keep it, because "knows" is clear and short.
[( )] Add more topics to the description.
[(X)] Replace "knows" with an observable action, such as "conducts a laboratory session following the safety checklist and records any incident".
[( )] Remove the word "safe" to shorten it.
[[?]] Which verb can a reader picture?
****
"Knows" describes an inner state. An observable action, object and standard give readers something they can picture and the assessor something they can check.
****

**Question 4.** Why write down the primary reader before drafting the claim?

[( )] Because readers must sign the specification.
[( )] Because the reader decides the badge colour.
[(X)] Because the decision the reader needs to make shapes what the claim must say and how much detail it needs.
[( )] Because the primary reader is always the issuing team.
[[?]] The claim serves a decision.
****
The reader's decision and constraints shape the level of detail and the wording. The issuing team is not normally the primary reader.
****

## Outcomes and criteria

### From claim to outcomes

A claim gives the overall statement. Learning outcomes break it into parts that can be taught and checked. Think of the claim as the headline and the outcomes as the main points under it.

Aim for three to six outcomes for a small credential. More than that is a sign that the credential is too large, or that the outcomes list tasks, not capabilities. Each outcome should follow the same pattern as the claim: an action verb, an object and a context or standard.

For the grant proposal claim above, outcomes could be:

1. Identifies a funder whose published priorities match a project.
2. Writes a need statement supported by at least two sources.
3. Builds a budget that matches the planned activities.
4. Checks a draft against the funder's guidelines before submission.

Outcomes describe what the earner can do. They do not describe what the course covers. "Covers budgeting" is a topic; "Builds a budget that matches the planned activities" is an outcome.

### What criteria are

Criteria are the conditions the earner must meet to be awarded the credential. In the Open Badges standard, criteria describe what is required, and they are a core part of the achievement description. A reader uses criteria to judge how demanding the credential is. An assessor uses them to decide who passes.

An outcome says what the earner can do. A criterion says what must be shown, and to what standard, for the award. Often one outcome leads to one criterion, but sometimes an outcome needs two criteria, or two outcomes share one.

Good criteria have these qualities:

- **Observable.** An assessor can see or read something that shows it.
- **Specific.** The standard is stated, for example "all three sections complete" or "within the agreed tolerance".
- **Independent.** One criterion does not depend on another to be judged.
- **Proportionate.** The demand matches the level and workload of the credential.
- **Complete.** Together the criteria cover the claim, with no outcome left without a criterion.

Add an award rule. State whether the earner must meet all criteria or a defined number of them. If some criteria are optional, say so.

{{1}}
<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Claim, outcomes and criteria as a tree</title>
  <desc>A tree diagram. One claim at the top branches into three outcomes. Each outcome connects to one criterion below it. A note states that every outcome needs at least one criterion.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="250" y="25" width="300" height="60" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="62" text-anchor="middle" font-size="18" fill="#FFFFFF" font-weight="bold">Claim</text>
  <line x1="400" y1="85" x2="400" y2="115" stroke="#02375B" stroke-width="2"/>
  <line x1="130" y1="115" x2="670" y2="115" stroke="#02375B" stroke-width="2"/>
  <line x1="130" y1="115" x2="130" y2="145" stroke="#02375B" stroke-width="2"/>
  <line x1="400" y1="115" x2="400" y2="145" stroke="#02375B" stroke-width="2"/>
  <line x1="670" y1="115" x2="670" y2="145" stroke="#02375B" stroke-width="2"/>
  <rect x="40" y="145" width="180" height="70" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="130" y="175" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Outcome A</text>
  <text x="130" y="198" text-anchor="middle" font-size="14" fill="#02375B">what they can do</text>
  <rect x="310" y="145" width="180" height="70" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="175" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Outcome B</text>
  <text x="400" y="198" text-anchor="middle" font-size="14" fill="#02375B">what they can do</text>
  <rect x="580" y="145" width="180" height="70" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="670" y="175" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Outcome C</text>
  <text x="670" y="198" text-anchor="middle" font-size="14" fill="#02375B">what they can do</text>
  <line x1="130" y1="215" x2="130" y2="255" stroke="#02375B" stroke-width="2"/>
  <line x1="400" y1="215" x2="400" y2="255" stroke="#02375B" stroke-width="2"/>
  <line x1="670" y1="215" x2="670" y2="255" stroke="#02375B" stroke-width="2"/>
  <rect x="40" y="255" width="180" height="70" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="130" y="285" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Criterion A</text>
  <text x="130" y="308" text-anchor="middle" font-size="14" fill="#02375B">what must be shown</text>
  <rect x="310" y="255" width="180" height="70" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="285" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Criterion B</text>
  <text x="400" y="308" text-anchor="middle" font-size="14" fill="#02375B">what must be shown</text>
  <rect x="580" y="255" width="180" height="70" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="670" y="285" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Criterion C</text>
  <text x="670" y="308" text-anchor="middle" font-size="14" fill="#02375B">what must be shown</text>
  <text x="400" y="385" text-anchor="middle" font-size="14" fill="#4F6576">Every outcome needs at least one criterion.</text>
  <text x="400" y="410" text-anchor="middle" font-size="14" fill="#4F6576">Award rule: state how many criteria the earner must meet.</text>
</svg>

### Writing criteria that an assessor can use

Write each criterion as a short sentence that starts with the earner or an action. Include the standard. Compare:

- Weak: "Demonstrates good budgeting skills."
- Stronger: "Submits a budget in which every planned activity has a cost line and the total matches the sum of the lines."

The stronger version tells an assessor exactly what to check. Two assessors would reach the same decision.

Watch for these common faults:

- **Vague quality words.** "Good", "appropriate", "effective" and "sufficient" need a definition. If you keep one, say how it is judged, for example "appropriate, as defined in the checklist".
- **Attendance as criterion.** "Attends all sessions" shows presence. Use it only if presence is itself part of the claim, such as a safety induction.
- **Too many criteria.** A long list makes the credential hard to award and hard to read. Group related checks into one criterion with a checklist as supporting material.
- **Hidden criteria.** If the assessor uses a standard that is not written down, the criteria are incomplete. Write it down.

Criteria also tell the earner what to aim for. Publish them before the learning starts.

**Worked example: From outcomes to criteria**

*College or training provider.* A college offers a micro-credential in "Producing accessible documents". The claim: "Produces a document that meets the college's accessibility checklist." Outcomes and criteria (illustrative):

| Outcome | Criterion |
|---|---|
| Structures a document with headings | The submitted document uses heading styles in a logical order with no skipped levels. |
| Adds text alternatives to images | Every informative image has a text alternative of no more than 125 characters. |
| Checks colour contrast | All text meets the contrast ratio set in the checklist. |

Award rule: all three criteria must be met. The earner may resubmit once.

*Corporate academy.* An HR department awards "Onboarding buddy". The claim: "Supports a new colleague through their first 30 days using the onboarding plan." Criteria (illustrative):

| Outcome | Criterion |
|---|---|
| Plans the first week | A written first-week plan is shared with the new colleague before day one. |
| Holds check-ins | At least four logged check-ins in 30 days, each with a short note of topics. |
| Gathers feedback | The new colleague completes the feedback form and the buddy records one improvement action. |

Award rule: all three criteria must be met.

**Practice activity: Break your claim into outcomes and criteria**

Continue your specification with sections 2 and 3.

1. Write three to five outcomes that together make up your claim.
2. For each outcome, write at least one criterion with a stated standard.
3. Replace any vague quality word, or define it.
4. Write the award rule in one sentence.
5. Swap your table with a peer. Ask: "Could two assessors reach the same decision from this criterion?" Mark any criterion that fails and revise it.

<details>
<summary>Facilitator notes</summary>

**Workshop option (60 minutes).** Run a "two assessors" exercise. Give pairs a deliberately vague criterion such as "Communicates effectively" and ask each person to write what they would check. Compare lists. The differences show why a standard is needed. Then ask pairs to rewrite the criterion.

**Watch for.** Participants copying a course syllabus into the criteria list. Redirect to what the earner shows, not what the course teaches.
</details>

### Check your understanding

**Question 1.** Which statement is the best criterion?

[( )] Demonstrates effective teamwork.
[( )] Participates in all workshop sessions.
[(X)] Submits a team log in which the earner records at least three tasks they completed and the outcome of each.
[( )] Shows a positive attitude to colleagues.
[[?]] Choose the one that an assessor can check in the same way as another assessor.
****
The third option names what is submitted and the amount. Two assessors would reach the same decision. The others rely on judgement words or on attendance.
****

**Question 2.** A credential has four outcomes and three criteria. One outcome has no criterion. What is the problem?

[( )] Nothing: criteria are optional extras.
[(X)] The criteria do not cover the claim, so the award does not show that outcome.
[( )] There are too few outcomes.
[( )] The award rule must be removed.
[[?]] Think about completeness.
****
Every outcome needs at least one criterion, or the credential awards something it never checks.
****

**Question 3.** What does an award rule state?

[( )] The price of the credential.
[( )] The colour of the badge.
[(X)] How many criteria, and which ones, the earner must meet to receive the credential.
[( )] The number of earners who may hold the credential.
[[?]] It decides who passes.
****
The award rule says how criteria combine into a decision, for example all criteria or a defined minimum.
****

**Question 4.** Why should criteria be published before the learning starts?

[( )] So that issuers can change them without notice.
[(X)] So earners know what to aim for and assessors apply the same standard.
[( )] So the metadata can be shorter.
[( )] So that no evidence is needed.
[[?]] Who benefits from knowing the criteria in advance?
****
Published criteria guide earners and make assessment consistent. They do not replace evidence or metadata.
****

## Evidence that proves the claim

### What counts as evidence

Evidence is what the earner shows, and what the issuer checks, to prove that a criterion is met. A criterion says what must be true. Evidence is the thing you look at to see that it is true.

Evidence takes many forms:

- A **work product**, such as a report, a design file, a lesson plan or a spreadsheet.
- A **performance record**, such as an observation checklist completed by an assessor.
- A **test result**, from a knowledge test or practical test.
- A **log or portfolio**, such as a reflective journal with dated entries.
- A **third-party statement**, such as a manager's confirmation or a client's feedback.

Choose the type that fits the verb in the criterion. A criterion with "builds" needs a product. A criterion with "facilitates" needs observation or a recording. A criterion with "explains" can use a short written or oral task.

Evidence must also be authentic: it is the earner's own work, produced under the conditions the issuer states. Say how authenticity is checked, for example through supervised tasks, a signed declaration, or a short viva.

### Matching evidence to each criterion

Build an evidence table. Each criterion gets a row. For each row, state the evidence, who judges it, and the standard of judgement.

{{1}}
<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Evidence table linking criteria to evidence and judge</title>
  <desc>A three-column table graphic. Column one lists criteria, column two lists the evidence that proves each criterion, and column three names who judges the evidence. Three rows show a product, an observation and a third-party statement.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="40" y="30" width="230" height="50" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="155" y="62" text-anchor="middle" font-size="16" fill="#FFFFFF" font-weight="bold">Criterion</text>
  <rect x="285" y="30" width="270" height="50" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="420" y="62" text-anchor="middle" font-size="16" fill="#FFFFFF" font-weight="bold">Evidence</text>
  <rect x="570" y="30" width="190" height="50" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="665" y="62" text-anchor="middle" font-size="16" fill="#FFFFFF" font-weight="bold">Judged by</text>
  <rect x="40" y="100" width="230" height="80" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="155" y="146" text-anchor="middle" font-size="14" fill="#02375B">Builds a budget</text>
  <rect x="285" y="100" width="270" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="420" y="146" text-anchor="middle" font-size="14" fill="#02375B">Work product: budget file</text>
  <rect x="570" y="100" width="190" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="665" y="146" text-anchor="middle" font-size="14" fill="#02375B">Assessor + checklist</text>
  <rect x="40" y="200" width="230" height="80" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="155" y="246" text-anchor="middle" font-size="14" fill="#02375B">Facilitates a meeting</text>
  <rect x="285" y="200" width="270" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="420" y="246" text-anchor="middle" font-size="14" fill="#02375B">Observation record</text>
  <rect x="570" y="200" width="190" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="665" y="246" text-anchor="middle" font-size="14" fill="#02375B">Trained observer</text>
  <rect x="40" y="300" width="230" height="80" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="155" y="346" text-anchor="middle" font-size="14" fill="#02375B">Applies the method at work</text>
  <rect x="285" y="300" width="270" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="420" y="346" text-anchor="middle" font-size="14" fill="#02375B">Manager statement</text>
  <rect x="570" y="300" width="190" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="665" y="346" text-anchor="middle" font-size="14" fill="#02375B">Line manager</text>
  <text x="400" y="420" text-anchor="middle" font-size="14" fill="#4F6576">One evidence row for every criterion.</text>
</svg>

### Rigor: the quality of the proof

Rigor means that the evidence really supports the claim and that different assessors judge it in the same way. Four checks help you test your design.

1. **Validity.** Does this evidence show the criterion, or something near it? A multiple-choice test about giving feedback does not show that someone gives feedback well.
2. **Sufficiency.** Is there enough evidence? One short task may not show a skill that must hold across situations.
3. **Authenticity.** Is it the earner's own work?
4. **Consistency.** Is there a rubric or checklist so that assessors reach the same decision?

Add proportion. A credential of five hours does not need a portfolio of thirty items. A credential that supports a safety-critical decision needs stronger proof than one that marks participation in a community event.

Also decide how evidence is stored and shared. Open Badges 3.0 allows evidence to be linked from a credential. Be careful with personal data: if evidence contains information about other people, such as client names or learner work, get consent or use anonymised samples. Check your organisation's data protection rules.

State the assessor. Who is allowed to judge the evidence, and what training do they need? An assessor who knows the earner personally may need a second marker.

**Worked example: Evidence plan**

*University or training provider.* A university short course awards "Conducting a literature search". Criterion: "Submits a search record showing at least three databases, the search terms used and the number of results at each stage." Evidence: a one-page search log, plus a short screen recording of one search, produced during a supervised session. Judged by: the course tutor, using a four-line checklist. Authenticity: the supervised recording. Sufficiency: one full search on a topic chosen from a list. Storage: the log is linked as evidence; the recording is kept by the university for twelve months (illustrative).

*Corporate academy.* An HR department awards "Facilitating a team retrospective". Criterion: "Facilitates a retrospective for a team of at least five people, covering what went well, what did not and agreed actions." Evidence: an observation form completed by a trained observer, and the action list produced by the team. Judged by: the observer, using the form. Authenticity: the observer attends in person. Sufficiency: one full session. Storage: the action list is shared only with the team's consent.

**Practice activity: Build your evidence table**

Continue your specification with section 4.

1. Create a table with one row per criterion from Module 2.
2. For each row, name the evidence, who judges it and the standard.
3. Add a line on authenticity and a line on sufficiency.
4. Mark any evidence that contains personal data and note how you handle it.
5. Check each row for validity: would the evidence still be convincing if you did not know the earner?

<details>
<summary>Facilitator notes</summary>

**Workshop option (60 minutes).** Evidence gallery. Each participant posts one criterion and its proposed evidence on a wall or shared board. Others add sticky notes with one of four labels: valid, insufficient, hard to authenticate, hard to judge. Participants revise their table with the notes.

**Discussion prompt.** Ask: "What is the cheapest evidence that still convinces a sceptical reader?" The answer often reduces over-collection.
</details>

### Check your understanding

**Question 1.** A criterion reads: "Facilitates a feedback conversation." Which evidence is the most valid?

[( )] A multiple-choice test on feedback theory.
[( )] A certificate of attendance at a feedback workshop.
[(X)] An observation record from a trained observer who watched the earner hold a feedback conversation.
[( )] A self-rating of confidence from 1 to 5.
[[?]] Match the type of evidence to the verb.
****
Facilitating is a performance, so an observation of the performance is the most valid evidence. A test, attendance or self-rating shows something nearby.
****

**Question 2.** What does "authenticity" mean for evidence?

[( )] The evidence looks professional.
[(X)] The evidence is the earner's own work, produced under the conditions the issuer states.
[( )] The evidence is stored in a public place.
[( )] The evidence is long.
[[?]] Whose work is it?
****
Authenticity concerns whether the work belongs to the earner and was produced under stated conditions, for example supervision or a signed declaration.
****

**Question 3.** Two assessors reach different decisions on the same evidence. Which change helps most?

[( )] Ask the earner to submit more items.
[(X)] Add a rubric or checklist with stated standards and train the assessors to use it.
[( )] Remove the criterion.
[( )] Let the earner choose the assessor.
[[?]] Look for consistency.
****
A shared rubric or checklist, with assessor training, supports consistent judgement. More items or a chosen assessor does not address the cause.
****

**Question 4.** Evidence for a criterion includes screenshots with client names. What should the designer do first?

[( )] Publish the screenshots on the credential page.
[( )] Delete the criterion.
[(X)] Check data protection rules, and get consent or use anonymised samples before the evidence is shared.
[( )] Ask the clients to sign the badge.
[[?]] Think about personal data of other people.
****
Evidence that contains other people's personal data needs consent or anonymisation, and must follow the organisation's data protection rules.
****

## Metadata for portability

### Why metadata matters

Metadata is structured information about a credential. It travels with the credential so that other systems, and other people, can read it. If the claim, criteria and evidence are the content of the specification, metadata is the label on the outside that lets a credential move between a learning platform, a wallet, an employer's system and a profile page.

Two standards help with this:

- **Open Badges 3.0** describes how to issue and verify digital badges as verifiable credentials. It carries information about the issuer, the achievement, the earner and the evidence.
- **Comprehensive Learner Record (CLR) Standard 2.0** describes how to package several achievements, with fuller detail, into a learner record.

Status as of November 2026; check before publishing. Both are current specifications. Platform support is still uneven, so check the conformance certification of any tool before you rely on it. <!-- VERIFY: current conformance certification status and list of certified products for Open Badges 3.0 and CLR 2.0 before publishing. -->

You do not need to write code to complete this part. Your task is to decide the content of each field. A technical team or a tool can then place it in the correct format.

{{1}}
<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Metadata card with labelled fields</title>
  <desc>A card showing eight labelled metadata fields of a credential: name, description, issuer, criteria link, evidence, alignment, level and workload, and dates. Each field is a labelled box inside the card.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="50" y="20" width="700" height="410" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="55" text-anchor="middle" font-size="18" fill="#02375B" font-weight="bold">Credential metadata card</text>
  <rect x="80" y="75" width="320" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="95" y="100" font-size="14" fill="#4F6576">Name</text>
  <text x="95" y="123" font-size="14" fill="#02375B">Short, specific title</text>
  <rect x="410" y="75" width="310" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="425" y="100" font-size="14" fill="#4F6576">Description</text>
  <text x="425" y="123" font-size="14" fill="#02375B">Claim in plain language</text>
  <rect x="80" y="150" width="320" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="95" y="175" font-size="14" fill="#4F6576">Issuer</text>
  <text x="95" y="198" font-size="14" fill="#02375B">Who vouches for it</text>
  <rect x="410" y="150" width="310" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="425" y="175" font-size="14" fill="#4F6576">Criteria</text>
  <text x="425" y="198" font-size="14" fill="#02375B">What was required</text>
  <rect x="80" y="225" width="320" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="95" y="250" font-size="14" fill="#4F6576">Evidence</text>
  <text x="95" y="273" font-size="14" fill="#02375B">What proves it</text>
  <rect x="410" y="225" width="310" height="60" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="425" y="250" font-size="14" fill="#02375B">Alignment</text>
  <text x="425" y="273" font-size="14" fill="#02375B">Framework or standard</text>
  <rect x="80" y="300" width="320" height="60" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="95" y="325" font-size="14" fill="#02375B">Level and workload</text>
  <text x="95" y="348" font-size="14" fill="#02375B">Level, hours, credit if any</text>
  <rect x="410" y="300" width="310" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="425" y="325" font-size="14" fill="#4F6576">Dates</text>
  <text x="425" y="348" font-size="14" fill="#02375B">Issue date, expiry if any</text>
  <text x="400" y="400" text-anchor="middle" font-size="14" fill="#4F6576">Shaded fields are the ones designers often leave empty.</text>
</svg>

### The fields to complete

Complete each of these fields in your specification. Use plain language first. A technical team can map it later.

- **Name.** A short, specific title. See Module 5.
- **Description.** The claim in one or two sentences a reader can follow without extra context.
- **Issuer.** The organisation that vouches for the credential, with a contact route.
- **Criteria.** The criteria and award rule, in a form that can be published and linked.
- **Evidence.** What the earner submits, and whether it is attached or linked.
- **Alignment.** The framework, standard or competency description the credential relates to. Alignment lets a reader place your credential in a wider system, for example a national qualifications framework, an occupational standard or a professional competence framework. Name the specific framework and the specific item, not only the framework in general.
- **Level.** The level of the credential on a stated framework, such as the European Qualifications Framework (EQF) or a national framework. State the framework as well as the number. Do not assign a level you cannot support with evidence. If the credential is not formally levelled, say so.
- **Workload.** The typical learning time. State whether it is notional learning hours, contact hours or both. If credit applies, name the credit system, for example ECTS, and state the amount only if an institution has confirmed it.
- **Dates and validity.** Issue date and, if relevant, expiry or renewal rule.
- **Language.** The language of the credential and the assessment.

The EU Council Recommendation of 2022 on a European approach to micro-credentials is a stable reference for what such credentials should describe. It lists elements such as the identification of the learner, title, issuing body, date, learning outcomes, notional workload in ECTS credits where possible, level and type of assessment. Check the text for the exact list. Status as of November 2026; check before publishing. Watch for Commission implementation reporting and national transpositions, because national practice may add or change requirements. <!-- VERIFY: exact list of information elements in the 2022 Council Recommendation on a European approach to micro-credentials, and current state of national transpositions. -->

### Honest metadata

Metadata is a promise. Check each field against what you can support.

- Do not claim alignment to a framework unless you have compared your criteria with it. Record who did the comparison and when.
- Do not state a level or credit amount because it sounds more valuable. State it only where a body with the authority to set it has done so, or say "not formally levelled".
- Keep workload honest. Count what a typical earner needs, including assessment time. If the figure is an estimate, say so.
- Keep metadata consistent with the description and criteria. If the description promises more than the criteria check, readers will notice.

**Worked example: Filling the metadata card**

*University or training provider.* A university continuing education unit issues "Conducting a literature search". Metadata (illustrative): Issuer: the unit's name and contact email. Alignment: the university's own information literacy statement, items 2 and 3, compared by the librarian on a stated date. Level: "Not formally levelled; designed at the level of first-year undergraduate study." Workload: "Notional learning 6 hours, including 1 hour of assessment." Credit: "None." Validity: "No expiry." Language: English.

*Corporate academy.* An HR department issues "Facilitating a team retrospective". Metadata (illustrative): Issuer: the academy and a named programme owner. Alignment: the company's internal leadership competency model, competency "Enable team learning", compared by the HR business partner. Level: "Internal level 2 of 4 in the company model." Workload: "Notional learning 8 hours including one observed session." Validity: "Two years, then renew by observed session." Language: English.

Note that both examples say what a field does not claim, as well as what it does.

**Practice activity: Complete your metadata card**

Continue your specification with section 5.

1. Fill in every field in the list above for your credential.
2. Name one framework or standard for alignment, name the specific item, and note how you compared it. If you cannot name one, write "none yet" and note what you would need to do.
3. State level on a named framework or write "not formally levelled".
4. State workload in hours, say what the hours include, and mark it as an estimate if it is one.
5. Highlight any field where you are unsure, and list who could confirm it.

<details>
<summary>Facilitator notes</summary>

**Workshop option (45 minutes).** Metadata clinic. Invite a technical colleague or a platform administrator to show how a credential record looks in a tool that supports Open Badges 3.0, without naming or promoting a product. Participants check that each field they decided on has a home in the tool. Discuss which fields the tool cannot hold and how to handle them.

**Caution.** Remind participants not to copy alignment statements from other credentials without checking.
</details>

### Check your understanding

**Question 1.** What is the main purpose of alignment metadata?

[( )] To make the badge image larger.
[(X)] To let a reader place the credential in a named framework or standard.
[( )] To replace the criteria.
[( )] To hide the issuer's name.
[[?]] Think about reading across systems.
****
Alignment points to a named framework, standard or competency item, so readers and systems can relate the credential to something they already know.
****

**Question 2.** A designer wants to put "EQF level 6" on a short workshop badge without any formal levelling. What is the best approach?

[( )] Add it, because it raises the badge's value.
[( )] Add "EQF level 8" to be safe.
[(X)] State "not formally levelled" and describe the intended level in words, unless an authorised body has set a level.
[( )] Leave the level field with a random number.
[[?]] Metadata is a promise.
****
A level should be stated only where it can be supported. If it is not formally levelled, say so and describe the intended level in plain words.
****

**Question 3.** Which workload statement is the clearest?

[( )] "Short course."
[( )] "Around a day or so."
[(X)] "Notional learning 6 hours, including 1 hour of assessment (estimate)."
[( )] "Intensive."
[[?]] Look for hours, what they include, and honesty about the estimate.
****
The third option gives a number, says what it includes and marks it as an estimate. The others are too vague for a reader to compare.
****

**Question 4.** What should a designer do to check which tools support Open Badges 3.0 and CLR 2.0?

[( )] Assume all tools support both fully.
[( )] Ask earners to test the badges.
[(X)] Check the conformance certification of the tool, because platform support is still uneven.
[( )] Remove the metadata fields that a tool does not show.
[[?]] Support varies between tools.
****
Both specifications are current, but support differs between tools. Conformance certification is the way to check what a tool does.
****

## Naming and description

### Names that readers can use

The name of a credential is the first thing a reader sees. It appears on a profile page, in a CV, in a search result and in a wallet. Often it is the only thing a reader sees. A weak name sends the reader away.

A good name is:

- **Specific.** It names the capability, not just the subject. "Facilitating a team retrospective" tells more than "Agile level 1".
- **Short.** Aim for six words or fewer where you can, and keep it readable in a narrow list.
- **Honest.** It does not suggest more than the criteria check. Avoid words such as "master", "expert" or "professional" unless the criteria support them.
- **Free of internal code.** "ACAD-204" means nothing to an outside reader. Keep codes in the identifier field.
- **Consistent.** If you issue a family of credentials, use a common pattern.

A name that starts with a verb, such as "Planning a small project" or "Writing accessible documents", often reads well and ties to the claim.

{{1}}
<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Weak and strong credential names compared</title>
  <desc>Two columns compare names. The left column lists weak names: Leadership level 1, Module 4 complete, and Agile expert. The right column lists stronger names: Leading a team meeting, Writing accessible documents, and Facilitating a team retrospective. A caption says that a strong name states the capability.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="50" y="30" width="330" height="50" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="215" y="62" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Weak names: vague or inflated</text>
  <rect x="420" y="30" width="330" height="50" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="585" y="62" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Stronger names: state the capability</text>
  <rect x="50" y="110" width="330" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="215" y="146" text-anchor="middle" font-size="14" fill="#02375B">Leadership level 1</text>
  <rect x="50" y="190" width="330" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="215" y="226" text-anchor="middle" font-size="14" fill="#02375B">Module 4 complete</text>
  <rect x="50" y="270" width="330" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="215" y="306" text-anchor="middle" font-size="14" fill="#02375B">Agile expert</text>
  <rect x="420" y="110" width="330" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="585" y="146" text-anchor="middle" font-size="14" fill="#02375B">Leading a team meeting</text>
  <rect x="420" y="190" width="330" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="585" y="226" text-anchor="middle" font-size="14" fill="#02375B">Writing accessible documents</text>
  <rect x="420" y="270" width="330" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="585" y="306" text-anchor="middle" font-size="14" fill="#02375B">Facilitating a team retrospective</text>
  <text x="400" y="395" text-anchor="middle" font-size="14" fill="#4F6576">A reader should know what the earner can do from the name alone.</text>
</svg>

### Descriptions that carry the claim

The description is the claim in a form that fits a profile card. Two or three sentences are enough. A reader should learn who the credential is for, what the earner can do and how it was checked, without opening any link.

A useful structure:

1. **What the earner can do.** The claim, in plain words.
2. **How it was checked.** One sentence on the evidence and assessment.
3. **Context.** Who issues it, and the workload or level if it helps.

Example (illustrative): "The earner plans a small project with a scope statement, a schedule and a risk register, and reports progress to a sponsor. Assessed through a submitted project plan judged against a four-point checklist. Issued by the academy's project office after about eight hours of study."

Keep the description consistent with the criteria. Do not add promises, such as job outcomes, that the criteria do not check. Never state that holding the credential proves competency in a job. Say what was assessed and how.

Use words the reader knows. Spell out abbreviations on first use. Write in active voice and keep sentences short.

### Using AI to draft descriptions, with a human edit log

You may use an AI writing tool to draft a name or description. This is optional. If you do, follow three rules.

1. **Give it your specification, not a topic.** Provide the claim, criteria and evidence plan. Ask for a description that restates them in plain language. A tool given only a topic will invent content.
2. **Edit as a human.** Check every sentence against your criteria. Remove anything the criteria do not support. Check names, numbers and framework references; a tool may state them wrongly.
3. **Keep a human edit log.** Record what the tool produced, what you changed and why. Add your name and the date. The log is part of your evidence.

Do not paste personal data, confidential material or learner work into a tool unless your organisation's policy allows it. Check the policy first.

A simple edit log (illustrative):

| Tool draft (extract) | Human change | Reason |
|---|---|---|
| "Guarantees readiness for senior roles." | Deleted. | Criteria do not check readiness for any role. |
| "Covers a wide range of project skills." | "Plans a small project with a scope statement, schedule and risk register." | Vague; replaced with the claim. |
| "Assessed by experts." | "Assessed by the project office using a four-point checklist." | Names who assessed and how. |

**Worked example: Rewriting a name and description**

*College or training provider.* A college's draft: Name: "Digital Skills Module 3". Description: "Learn about spreadsheets and data." Rewritten: Name: "Analysing data in a spreadsheet". Description: "The earner cleans a data set, builds a summary table and a chart, and explains one finding in two sentences. Assessed through a submitted spreadsheet judged against a checklist. Issued by the college's digital skills team after about ten hours of study." Changes: the name states the capability, the description restates the claim and says how it was checked.

*Corporate academy.* An HR draft: Name: "Feedback Champion". Description: "Recognises excellence in giving feedback." Rewritten: Name: "Holding a feedback conversation". Description: "The earner prepares and holds a structured feedback conversation with a team member and records agreed actions within two working days. Assessed by a trained observer using a checklist. Issued by the academy after about six hours of learning including one observed conversation." Changes: "Champion" and "excellence" suggest more than the criteria check, so they are removed.

**Practice activity: Name and describe your credential**

Continue your specification with section 6.

1. Write three possible names. Choose one and note why.
2. Write a description of two or three sentences following the structure above.
3. Check that every statement in the description is supported by a criterion or evidence row.
4. Optional: ask an AI writing tool to draft the description from your specification. Keep an edit log with at least three entries, as in the table above. If you do not use a tool, write "No AI used" in your log.
5. Read the name and description aloud to a colleague. Ask them what the earner can do. If the answer differs from your claim, revise.

<details>
<summary>Facilitator notes</summary>

**Workshop option (45 minutes).** Name swap. Each participant writes their credential name on a card. Cards are swapped and each person writes, in one sentence, what they think the earner can do. The original author compares and revises.

**AI discussion (15 minutes).** Ask participants who used a tool to share one sentence the tool wrote that was wrong or unsupported. Collect examples. Reinforce that the human edit log is required, and check that participants have not shared confidential material with a tool.
</details>

### Check your understanding

**Question 1.** Which name is the best for a credential?

[( )] Level 1 Master Practitioner
[( )] ACAD-204
[(X)] Writing accessible documents
[( )] Excellence in documents
[[?]] Look for a specific capability, free of codes and hype.
****
The third option states a capability. The others use a level label, an internal code or a vague, inflated word.
****

**Question 2.** What should a good description contain?

[( )] The earner's personal details and test scores.
[(X)] What the earner can do, how it was checked, and the issuer with workload or level where useful.
[( )] A list of every topic covered in the course.
[( )] A promise about future job success.
[[?]] Think of the claim, the check and the context.
****
A description states the claim, says how it was checked and gives context. It does not list topics, include personal data or promise job outcomes.
****

**Question 3.** A designer uses an AI tool to draft a description. Which step is required?

[( )] Publish the draft as it is, because the tool is accurate.
[( )] Delete the criteria to match the draft.
[(X)] Edit the draft against the specification as a human and keep an edit log of what changed and why.
[( )] Ask the tool to write the criteria as well.
[[?]] A person remains responsible.
****
A human must check the draft against the claim and criteria and record changes in an edit log. The tool does not replace that responsibility.
****

**Question 4.** An AI draft says "Guarantees readiness for senior roles". What should the designer do?

[( )] Keep it, because it is positive.
[(X)] Delete it, because the criteria do not check that, and log the change with the reason.
[( )] Move it to the badge image.
[( )] Add a criterion to match it without evidence.
[[?]] The description must match what is checked.
****
A description may not promise more than the criteria check. Delete the statement and record the change and reason in the edit log.
****

## Testing with readers

### Why test with someone outside the team

The people who design a credential know what they mean. That knowledge hides problems. They fill gaps without noticing, and they read their own text as they intended it. A reader outside the team has no such help. They show you what the credential says to someone who was not in the room.

Testing is part of rigor, and it also checks value: does the credential mean something to the people who will read it? A short test with one or two readers often finds problems that review within the team does not.

Choose readers who match the primary reader you defined in Module 1: for example an employer, a selector, a supervisor from another department, or a person from a partner organisation. Do not choose someone who helped design the credential. Avoid using only friendly colleagues who will not challenge you.

{{1}}
<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg" font-family="Open Sans, Arial, sans-serif">
  <title>Test and revise loop with an outside reader</title>
  <desc>A loop with four steps arranged clockwise: draft the specification, give it to an outside reader, observe and record what the reader says, then revise. An arrow returns from revise to the reader step for a second round. A label states that the reader is outside the issuing team.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="60" y="40" width="250" height="80" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="185" y="72" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">1. Draft</text>
  <text x="185" y="98" text-anchor="middle" font-size="14" fill="#02375B">Specification and card</text>
  <rect x="490" y="40" width="250" height="80" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="615" y="72" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">2. Reader</text>
  <text x="615" y="98" text-anchor="middle" font-size="14" fill="#02375B">Outside the issuing team</text>
  <rect x="490" y="290" width="250" height="80" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="615" y="322" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">3. Observe</text>
  <text x="615" y="348" text-anchor="middle" font-size="14" fill="#02375B">Record what the reader says</text>
  <rect x="60" y="290" width="250" height="80" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="185" y="322" text-anchor="middle" font-size="16" fill="#FFFFFF" font-weight="bold">4. Revise</text>
  <text x="185" y="348" text-anchor="middle" font-size="14" fill="#FFFFFF">Change and log the change</text>
  <line x1="310" y1="80" x2="490" y2="80" stroke="#02375B" stroke-width="2"/>
  <polygon points="490,80 478,74 478,86" fill="#02375B"/>
  <line x1="615" y1="120" x2="615" y2="290" stroke="#02375B" stroke-width="2"/>
  <polygon points="615,290 609,278 621,278" fill="#02375B"/>
  <line x1="490" y1="330" x2="310" y2="330" stroke="#02375B" stroke-width="2"/>
  <polygon points="310,330 322,324 322,336" fill="#02375B"/>
  <line x1="185" y1="290" x2="185" y2="120" stroke="#02375B" stroke-width="2"/>
  <polygon points="185,120 179,132 191,132" fill="#02375B"/>
  <text x="400" y="215" text-anchor="middle" font-size="16" fill="#02375B" font-weight="bold">Repeat if needed</text>
  <text x="400" y="240" text-anchor="middle" font-size="14" fill="#4F6576">Second round with a different reader</text>
  <text x="400" y="420" text-anchor="middle" font-size="14" fill="#4F6576">The reader sees only what a real reader would see.</text>
</svg>

### How to run a reader test

A reader test can be short. Thirty minutes with one reader is a good start. Follow these steps.

1. **Prepare what the reader sees.** Give them only what a real reader would see: the name, description, criteria summary and metadata card. Do not explain it first.
2. **Ask them to tell you in their own words.** "What can this earner do?" "What did the earner have to show?" "How demanding is this, compared with others you know?"
3. **Ask a decision question.** "Would this help you decide whether to [the decision you named in Module 1]? What else would you need?"
4. **Watch for confusion.** Note where the reader hesitates, rereads or asks a question. Each is a point to fix.
5. **Do not defend.** Your task is to listen. If you explain or argue, you lose the information.
6. **Record the results.** Keep a short log: reader role, what they said, what you changed.

Include a question on fairness and access. Ask whether any criterion could disadvantage a group of earners for reasons that have nothing to do with the claim, such as a time limit that is not part of the skill, or a format that needs equipment not everyone has. Adjust where the barrier is not part of the claim.

### Revising and recording

Sort the reader's comments into three groups.

- **Must fix.** The reader misunderstood the claim, could not tell what was required, or found a statement that the criteria do not support.
- **Should fix.** The reader found wording that is unclear or too long.
- **Note.** A reader preference that does not affect meaning.

Revise the must-fix items first. Change the specification, not only the description. If a reader cannot tell what the earner can do, the claim or criteria may need work, and polishing the description alone will not help.

Keep a revision log with the original text, the reader's comment, your change and the date. A second round with a different reader shows whether your changes worked.

Peer review in this course follows the same logic. Your peer is outside your issuing team, so they act as a reader. Give feedback as observations ("I read this as...") instead of verdicts ("this is wrong"), and base it on the rubric.

**Worked example: A reader test and a revision**

*University or training provider.* A university designs "Conducting a literature search". The designer asks a librarian from another faculty to read the card. The librarian says: "I see 'search record' but I cannot tell how many databases are needed or whether a recording counts." Must fix: the criterion states "at least three databases" in the criteria but the description says only "a search record". The designer changes the description to include "in at least three databases" and adds the recording to the evidence list. Revision log entry: reader role, quote, change, date.

*Corporate academy.* An HR department designs "Holding a feedback conversation". The designer asks a department head who was not involved. The department head says: "Does this mean they can run appraisals on their own? I would not assume that." Must fix: the description implied more than the criteria check. The designer changes "ready to appraise" to "holds a structured feedback conversation with a team member" and adds a line "This credential does not authorise formal appraisals." The department head also asks about people who work night shifts and cannot be observed during the day; the designer adds an alternative observation slot.

**Practice activity: Test and revise your specification**

Complete section 7 of your specification, and finish your draft.

1. Choose a reader outside your issuing team who matches your primary reader.
2. Give them only the name, description, criteria summary and metadata card.
3. Ask the three questions in the steps above and the decision question. Take notes. Do not explain.
4. Sort comments into must fix, should fix and note. Revise the specification.
5. Write a revision log with at least three entries: the reader's comment, your change and the date.
6. Exchange your complete specification with your assigned peer. Review theirs using the rubric in "Assessment and badge" and write your peer review notes as observations.
7. Prepare your final submission: specification, reader test log and revision log, and peer review notes.

<details>
<summary>Facilitator notes</summary>

**Workshop option (90 minutes, live or online).** Run a structured peer review round. Pairs exchange specifications. Each reviewer reads for ten minutes in silence, then gives feedback in the order: what I understood the earner can do; where I hesitated; one thing that works well; one must-fix item. The author only listens and takes notes. Close with a five-minute whole-group debrief on the most common must-fix items.

**Handling difficulty.** If participants cannot find an outside reader, allow a colleague from another team or a peer from another pair, but not someone who contributed to the design. Record this in the log.

**Marking note.** Assessors should check that the revision log shows real changes to the specification and not only to wording.
</details>

### Check your understanding

**Question 1.** Who is the best reader for a test?

[( )] The designer's closest colleague who helped write it.
[( )] The head of the issuing team.
[(X)] A person outside the issuing team who matches the primary reader.
[( )] The designer, reading it again after a week.
[[?]] The reader should not share your knowledge.
****
A reader outside the team, matching the primary reader, shows what the credential says to someone without inside knowledge.
****

**Question 2.** During a reader test, the reader asks what a term means. What should the designer do?

[( )] Explain it fully and move on.
[( )] Tell the reader to read the course guide.
[(X)] Note the question as a point to fix, and avoid explaining so that the confusion is recorded.
[( )] End the test.
[[?]] Your task is to listen.
****
A question shows where the specification is unclear. Explaining it hides the problem and loses the information. Record it and revise the text.
****

**Question 3.** A reader says the description suggests more than the criteria check. How should this be classed and handled?

[( )] A preference to note only.
[(X)] A must-fix item: change the description, and the criteria if needed, so that they agree.
[( )] A reason to delete the reader's feedback.
[( )] A reason to add more promotional wording.
[[?]] Does it affect meaning or honesty?
****
A mismatch between description and criteria affects meaning and honesty, so it is must-fix. Align the text with what is actually checked.
****

**Question 4.** What should a revision log contain?

[( )] Only the final version of the description.
[( )] The reader's name and personal details.
[(X)] The original text, the reader's comment, the change made and the date.
[( )] A list of topics in the course.
[[?]] It shows what changed and why.
****
A revision log records what the reader said, what you changed and when, so that others can see the effect of the test.
****

## Assessment and badge

### The assessment task

You submit a complete credential specification for a real or realistic credential. A person assesses it with the ICoBC design rubric below. A peer also reviews it. The final knowledge check supports the assessment and covers all four learning outcomes.

**What to submit (badge evidence)**

1. **Credential specification.** Sections 1 to 6 of your template: claim, outcomes, criteria with award rule, evidence table, metadata card, and name and description.
2. **Reader test and revision log.** Section 7: the reader role, what the reader said, what you changed and when.
3. **Peer review notes.** The notes you wrote for your peer, based on the rubric, and a short note on how you used the notes you received.
4. **Human edit log (if you used AI).** Or the statement "No AI used".
5. **Rubric result.** Recorded by the assessor.

**Length.** The specification is usually three to five pages. Quality matters more than length.

### ICoBC design rubric

The assessor rates each row as Not yet, Meets or Exceeds. The assessor writes a short comment on each row.

| Row | Criterion | Not yet | Meets | Exceeds |
|---|---|---|---|---|
| 1. Claim | States what the earner can do, with an action verb, an object and a context or standard; names the primary reader | Uses inner-state verbs or lists topics; reader not named | Observable claim with all four parts; reader named | Claim is precise, reader decision is clear, and wording is free of ambiguity |
| 2. Outcomes | Three to six outcomes that together make up the claim | Outcomes list topics or do not match the claim | Outcomes state capabilities and cover the claim | Outcomes are well sequenced, proportionate to the workload, and trace clearly to the claim |
| 3. Criteria | Each outcome has at least one observable, specific criterion; award rule stated | Criteria are vague or missing for some outcomes; no award rule | Every outcome has a checkable criterion with a standard; award rule stated | Criteria are independent, proportionate, and two assessors would clearly reach the same decision |
| 4. Evidence | One evidence row per criterion with type, judge, standard, authenticity and sufficiency | Evidence is missing, does not fit the criterion or has no judge | Evidence is valid for each criterion, with judge and standard named | Evidence is proportionate, authenticity and data protection are handled, and a rubric or checklist supports consistent judgement |
| 5. Metadata | Metadata card complete; alignment, level and workload stated honestly | Fields missing, or level, credit or alignment claimed without support | All fields complete; alignment names a specific item; level and workload stated honestly | Alignment comparison recorded; limits of the claim stated; fields consistent with the criteria |
| 6. Name and description | Specific name; description states claim and how it was checked, in plain English | Name is vague or inflated; description promises more than the criteria check | Name states a capability; description matches the criteria and is clear | Name and description read well on their own; any AI use has a clear human edit log |
| 7. Testing and revision | Test with a reader outside the team; revisions recorded | No outside reader, or no revisions | Test run with a suitable reader; must-fix items revised and logged | Changes improve the claim or criteria, not only the wording; fairness and access considered; second round or peer feedback used |
| 8. Peer review | Peer review notes are specific and based on the rubric | Notes are general or absent | Notes are specific, observational and cover most rubric rows | Notes are constructive, cover all rows and show how feedback was used |

**Pass rule.** The earner passes when the assessor rates every row as Meets or Exceeds. If one or more rows are rated Not yet, the earner receives written feedback and may revise and resubmit once. The final knowledge check must also be completed. Passing the final check does not replace the rubric result.

**Link to outcomes.** Rows 1 to 3 assess outcome 1 and outcome 2. Row 4 assesses outcome 2. Rows 5 and 6 assess outcome 3. Rows 7 and 8 assess outcome 4.

<details>
<summary>Facilitator notes</summary>

**Assessor preparation.** Assessors should read the rubric together and score two sample specifications before live marking, then compare ratings and discuss differences. Record the outcome of this calibration.

**Marking.** Assessors write a short comment on each row. For a Not yet rating, the comment states the specific change needed. The assessor may not grade inside this file. Record the rubric result in the Kursbibliothek system.

**Badge issue.** Issue the badge "Designing a Credential: Claim, Criteria, Evidence and Metadata (Ability, L2)", alignment code ICSF-CRDS-L2-A, only when the pass rule is met and evidence items 1 to 3 are on file. A badge for this course shows that the earner has completed the assessed practice tasks. It does not show competence in any specific job.
</details>

### Final knowledge check

Answer all questions. You may revisit modules before you answer.

**Question 1.** Which claim best states what the earner can do?

[( )] Understands how to run workshops.
[( )] Completed a workshop on facilitation.
[(X)] Facilitates a 60-minute workshop for up to twelve people using a written plan and records agreed actions.
[( )] Is familiar with facilitation methods.
[[?]] Look for an action, object and standard.
****
The third option has an observable action, an object and a context. The others describe understanding, attendance or familiarity.
****

**Question 2.** A designer has five outcomes and the criteria cover only four of them. What should the designer do?

[( )] Leave it, because criteria are optional.
[(X)] Add a criterion for the remaining outcome, or remove the outcome if it is not part of the claim.
[( )] Remove the award rule.
[( )] Add a new outcome without a criterion.
[[?]] Every outcome needs a criterion.
****
The credential should check everything it claims. Add a criterion or remove the outcome.
****

**Question 3.** Which outcome is written as a capability rather than a topic?

[( )] Covers the principles of budgeting.
[( )] Introduction to risk registers.
[(X)] Builds a project budget in which every planned activity has a cost line.
[( )] Discussion of schedule methods.
[[?]] Look for what the earner does.
****
The third option states what the earner does, with an object and a standard. The others name topics or activities of the course.
****

**Question 4.** Which criterion is the most checkable?

[( )] Shows good judgement in client meetings.
[( )] Attends all planning sessions.
[(X)] Submits a client meeting plan with an agenda, three stated objectives and a follow-up action list.
[( )] Demonstrates professionalism.
[[?]] Two assessors should reach the same decision.
****
The third option states what is submitted and what it contains. The others rely on judgement words or attendance.
****

**Question 5.** A criterion reads: "Delivers a safe lifting demonstration." Which evidence has the highest validity?

[( )] A short written quiz on lifting rules.
[(X)] An observed demonstration judged by a trained assessor with a checklist.
[( )] A signed statement that the earner is confident.
[( )] A certificate of attendance at a safety talk.
[[?]] Match the evidence to the verb.
****
Delivering a demonstration is a performance, so observation by a trained assessor with a checklist is the most valid. Quiz, self-statement or attendance show something nearby.
****

**Question 6.** Which step best protects the authenticity of a written work product?

[( )] Ask the earner to make it longer.
[(X)] State the conditions of production, such as a supervised session or a signed declaration, and a short follow-up question on the work.
[( )] Publish it on a public page.
[( )] Remove the assessor.
[[?]] Authenticity means the work is the earner's own.
****
Authenticity is supported by stated production conditions and checks such as supervision, a declaration or a short viva.
****

**Question 7.** Which statement about level metadata is the most honest for a short workshop with no formal levelling?

[( )] EQF level 7.
[( )] Advanced level.
[(X)] Not formally levelled; designed at the level of introductory workplace practice.
[( )] Level 5, because it sounds right.
[[?]] State only what can be supported.
****
If no authorised body has set a level, say so and describe the intended level in plain words.
****

**Question 8.** Which workload statement is most useful to a reader?

[( )] Short.
[( )] Several days.
[(X)] Notional learning 8 hours, including 1 hour of assessment (estimate).
[( )] Intensive programme.
[[?]] Look for hours, scope and honesty.
****
It states a number, what it includes and that it is an estimate. The others cannot be compared.
****

**Question 9.** Which name is the best for a credential?

[( )] Excellence in Data
[( )] DS-301
[(X)] Cleaning and summarising a data set
[( )] Level 3 Data Master
[[?]] Choose a specific capability without codes or hype.
****
The third option states a capability. The others use hype, a code or a level label.
****

**Question 10.** A designer uses an AI tool to draft a description. What is required before the description is published?

[( )] Nothing, because the tool uses the specification.
[(X)] A human edit against the claim and criteria, and an edit log recording changes and reasons.
[( )] A second AI tool to check the first.
[( )] Removal of the criteria so the text matches.
[[?]] A person remains responsible.
****
A human must check each statement against the specification and keep an edit log. Tools can produce unsupported statements.
****

**Question 11.** A reader outside the team says the description suggests the earner is ready to carry out formal appraisals, but the criteria do not check that. What is the correct response?

[( )] Ignore it, because the reader is not an expert.
[(X)] Treat it as must-fix, align the description with the criteria and add a note on what the credential does not cover.
[( )] Add a criterion later without evidence.
[( )] Explain the intention to the reader and keep the text.
[[?]] Honesty and meaning are at stake.
****
A mismatch between description and criteria must be fixed. Align the text with what is checked and state limits where useful.
****

**Question 12.** Which peer review comment follows good practice?

[( )] "This is wrong."
[( )] "I like it."
[(X)] "I read criterion 2 as requiring two sources, but the evidence row says one. Which is intended?"
[( )] "You should start again."
[[?]] Observations tied to the specification help the author most.
****
A specific observation tied to the text, phrased as what the reader understood, helps the author revise. General verdicts do not.
****

### Evidence for the badge

| Item | Held by | Notes |
|---|---|---|
| Credential specification | Earner submits; issuer stores | Sections 1 to 6 of the template |
| Reader test and revision log | Earner submits; issuer stores | Section 7 |
| Peer review notes | Earner submits; issuer stores | Notes given and a short note on notes received |
| Human edit log or "No AI used" | Earner submits; issuer stores | Required if AI was used for any text |
| Rubric result | Assessor records | Row ratings and comments |

The badge is "Designing a Credential: Claim, Criteria, Evidence and Metadata (Ability, L2)", alignment code ICSF-CRDS-L2-A. It records that the earner completed assessed practice tasks on designing a credential specification. It does not show competence in any particular job.

## Sources and further reading

Status as of November 2026; check before publishing. All sources below are official texts or documents from standards bodies and framework owners. Check each for the current version before you cite it.

- **Open Badges 3.0.** Specification published by 1EdTech Consortium. Search for "Open Badges 3.0" on the 1EdTech website. <!-- VERIFY: current version, status and exact title on the 1EdTech website. -->
- **Comprehensive Learner Record (CLR) Standard 2.0.** Specification published by 1EdTech Consortium. <!-- VERIFY: current version, status and exact title on the 1EdTech website. -->
- **Conformance certification for Open Badges 3.0 and CLR 2.0.** Published by 1EdTech Consortium; check which tools are certified before you choose a platform. <!-- VERIFY: current certification programme and list of certified products. -->
- **Council Recommendation of 16 June 2022 on a European approach to micro-credentials for lifelong learning and employability.** Official Journal of the European Union. Search for the title on EUR-Lex. <!-- VERIFY: exact date, title and OJ reference on EUR-Lex. -->
- **European Qualifications Framework (EQF).** European Union. Use the official EU pages to check level descriptors before you state an EQF level. <!-- VERIFY: current official EQF pages and level descriptors. -->
- **ICoBC Credentialing Skills Framework (ICSF).** Owned by ICoBC, Berlin. Use the current published version for skill CRDS "Credential design" and level L2 descriptors. <!-- VERIFY: current version and publication location of ICSF. -->
- **W3C Verifiable Credentials Data Model.** Published by the World Wide Web Consortium. Background for how Open Badges 3.0 relates to verifiable credentials. <!-- VERIFY: current version and status. -->

**Time-sensitive points to check before publishing**

- Platform support for Open Badges 3.0 and CLR 2.0 is still uneven. Check conformance certification of tools.
- Watch for Commission implementation reporting and national transpositions of the 2022 Council Recommendation, because national requirements for micro-credentials may differ.
