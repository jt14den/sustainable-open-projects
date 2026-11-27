# Sustainable Open Projects: teachability review and local Codex brief

Reviewed: 25 November 2026. Research revision: 25 November 2026. Author: ChatGPT, at Tim Dennis's request.

## Research revision at a glance

The follow-up research supports the guided workshop direction and adds the UC OSPO Sustainability Playbook as an academic companion. Keep ITAV's four facets as the organizing structure. Give learners selected playbook references instead of a second framework to memorize.

Update the concepts around protected time, support boundaries, contributions beyond code, tested handover capability, preservation, and responsible endings. A stored release and a working service need separate plans. Qualify the teaching advice: support depends on prior knowledge, a short attempt may precede explanation, and successful worksheet completion does not establish retention or workplace use.

The final section, **Research update: concepts and the UC OSPO playbook**, contains a crosswalk, specific changes, source limits, and an annotated bibliography. Its qualifications govern the earlier recommendations. The original source-defect findings remain tied to the dated lesson snapshot; the lesson was not re-audited against later local edits during this research pass.

## Decision

**Develop this into a guided decision workshop. The current version is an outline that an experienced facilitator could expand, but it does not yet give another instructor enough material to teach its promised skills reliably.**

The problem is not excessive reading. The lesson is short. The problem is the amount of reasoning learners must supply between a definition and a complex project decision. Shortening the prose further would leave those gaps in place.

Keep the practical subject, the no-coding entry point, the three substantive topics, and the emphasis on context and tradeoffs. Add a shared case, demonstrations of reasoning, structured practice, and feedback. Finish with one small decision record that joins the topics together.

## Start here: prompt for Codex

Use this file in the local `sustainable-open-projects` repository. Paste the following into Codex:

```text
Read sustainable-open-projects-teachability-review.md in full. Improve this
Carpentries Workbench lesson locally using its implementation backlog,
sample activities, and acceptance criteria. Read the research update section
before implementing the recommendations; apply its qualifications to the
original design. Use ITAV as the main framework and selected UC OSPO playbook
sections as the academic companion. Recheck whether linked draft chapters
have developed since the pinned review. Do not modify the playbook repository.

First read applicable AGENTS.md files, git status, config.yaml, the episodes,
learner materials, profiles, and instructor notes. Compare the current files
with the review's dated evidence. Preserve user changes. If a finding has
already been fixed, retain the fix and adapt the remaining work.

Then implement the changes. Do not stop after producing another plan.
Use the proposed 120-minute introductory workshop as a working assumption.
Keep the no-coding prerequisite. Make the shared fictional case sufficient
for every required task. Retain optional application to learners' own projects.
Treat the sample content as a design specification that you may improve.
Include support boundaries, recurring and transition effort, a capability-based
handover check, and a compact citation/preservation/status note. Accept a
well-justified reduced scope or responsible sunset. Keep the workshop within
its stated introductory scope by replacing weak material rather than adding
new theory lectures. Make legal and funding-process questions referral tasks.

Complete P0 and P1 before optional extensions. Keep Sandpaper/Workbench and
the repository's conventions. Edit source Markdown and configuration, not
generated HTML. Do not copy the Teaching Tech Together book into the lesson.
Attribute ITAV sources and distinguish official activities from adaptations.

Run the repository's appropriate local validation and build. Inspect the
rendered learner, instructor, and all-in-one views. If dependencies are
unavailable, report exactly what could not run and perform the remaining
static checks. Do not count static checks as a successful build.

Return a concise change summary, changed files, checks and their results,
remaining uncertainties, and instructions for a human pilot. Keep all changes
local. Do not commit, push, open a PR, or publish.
```

## Evidence and limits

I read the published [all-in-one learner lesson](https://www.tim-dennis.com/sustainable-open-projects/aio.html), its summary/setup page, and its all-in-one instructor view. I also inspected the public repository's configuration, all four episode files, README, learner reference/setup files, learner profile, instructor notes, and main build workflow.

Repository snapshot: [`234a050c2507e290b1614a544939ad38e7f628b1`](https://github.com/jt14den/sustainable-open-projects/tree/234a050c2507e290b1614a544939ad38e7f628b1). Findings below refer to that snapshot. It matches the three substantive episodes on the reviewed site; I did not establish the site's deployment commit.

For *Teaching Tech Together*, I read chapters 2–6, 9–10, and 12, plus the lesson-study/feedback sections in chapter 8 and Appendix 21. This is a focused reading of the relevant teaching material, not a claim to have read every chapter or independently checked all the book's research citations. I also checked the official ITAV guidebook, its Appendix A, and the current toolkit descriptions.

| Conclusion | Evidence strength and limit |
| --- | --- |
| Required exercise inputs and feedback are incomplete | **Strong.** Direct source and published-page inspection establish the missing local inputs and lack of worked solutions. Instructor-supplied handouts could mitigate this, but none were included in the reviewed materials. |
| Beginners must supply too much unstated reasoning | **Moderate.** This follows from the gap between the explanations and tasks, assuming learners are new to project sustainability decisions. It could matter less in a facilitated session of experienced maintainers. |
| The revision will improve learning or fit its proposed duration | **Limited.** Neither version was observed in a classroom. Pilot performance and actual timings must determine this. |

I did not run the lesson build, observe teaching, or perform a full visual, keyboard, or assistive-technology audit. The list-rendering defects below were verified in the downloaded published HTML. I did not treat guessed support-page URLs as evidence of broken navigation.

## Teaching framework

Wilson's useful principles here are: establish learners' starting knowledge; build a usable mental model; design backward from demonstrable outcomes; show examples before independent work; use brief checks that expose misconceptions; support participation; and revise from observed learning. Practice should reveal reasoning, with feedback that tells the learner what to change.

References: [mental models and assessment](https://teachtogether.tech/en/index.html#s:models), [expertise and memory](https://teachtogether.tech/en/index.html#s:memory), [cognitive load](https://teachtogether.tech/en/index.html#s:architecture-load), [lesson design](https://teachtogether.tech/en/index.html#s:process), [classroom practice](https://teachtogether.tech/en/index.html#s:classroom), [motivation and accessibility](https://teachtogether.tech/en/index.html#s:motivation), and [exercise types](https://teachtogether.tech/en/index.html#s:exercises).

The specific diagnosis, case, exercises, timings, and implementation choices below are my editorial proposals. They have not been validated for this audience. Do not turn the book's memory-capacity examples into a fixed limit on how many concepts a person can learn, or use a supposed universal attention span to justify the schedule. Do not simplify a distinction until it becomes misleading.

## What is already useful

- The subject concerns real decisions that participants may face soon.
- Coding is not required. Most tasks can work with paper or an ordinary document.
- Each substantive episode has questions, objectives, practice, and key points.
- Context and tradeoffs are already acknowledged. Preserve that openness when writing solutions.
- Pair and group discussion provide a useful starting structure.

These are worthwhile foundations. They do not yet establish that the tasks teach the objectives: the missing connection is a visible method for making and assessing decisions.

## Ranked findings

### 1. Supply the missing exercise inputs and correct the worksheet reference — P0

**Verified:** [governance source, line 46](https://github.com/jt14den/sustainable-open-projects/blob/234a050c2507e290b1614a544939ad38e7f628b1/episodes/governance.md#L46) sends learners to Appendix A without a link or local copy. [Infrastructure source, line 49](https://github.com/jt14den/sustainable-open-projects/blob/234a050c2507e290b1614a544939ad38e7f628b1/episodes/infrastructure.md#L49) refers to a supplied tool list, but no such list appears in the episode or repository tree.

There is also a substantive reference mismatch. [ITAV Appendix A](https://itav.lyrasis.org/wp-content/uploads/2024/10/ITAV_Report_Interactive.pdf#page=43), printed page 41, is a sustainability worksheet covering all four facets. It asks for assessments of the program's strengths and weaknesses by facet. The lesson instead asks learners to rate the importance of governance characteristics and then choose a governance model. The appendix does not supply that decision procedure.

**Change:** Link the official source accurately. Replace the required exercise with the local decision worksheet specified below. Identify it as a lesson adaptation informed by ITAV. Do not invent an official ITAV governance-scoring instrument. If any numerical scale is retained, define what its endpoints mean and what evidence supports a judgment; it must not mechanically select a governance model.

**Done when:** A learner can begin and finish both activities using only the lesson and linked local materials. Every requested input exists and matches the task.

### 2. Make the ITAV framework visible and align the advertised scope — P0

**Verified:** The [overview](https://github.com/jt14den/sustainable-open-projects/blob/234a050c2507e290b1614a544939ad38e7f628b1/index.md#L7) promises community health, resource development, and phase alignment. The [configured sequence](https://github.com/jt14den/sustainable-open-projects/blob/234a050c2507e290b1614a544939ad38e7f628b1/config.yaml#L68) contains governance, community needs, and infrastructure. There is no substantive resources episode or taught phase-assessment method. The unlisted introduction is Workbench's Markdown demonstration, not an introduction to sustainability.

The [official ITAV toolkit](https://itav.lyrasis.org/toolkit/) has four facets: governance, technology, resources, and community engagement. The guidebook also explains that a program can occupy different phases in different facets. Treating its maturity as one project-wide label hides that distinction.

**Change:** Replace the unused template introduction with a short sustainability introduction. Explain the four facets using the case. Show that an established website may coexist with fragile staffing or unclear decision authority. Keep resources visible as labor, money, institutional support, and continuity constraints in later activities. Include maintaining, reducing scope, handing over, and responsibly ending support as possible choices; distinguish preserving a scholarly artifact from continuing a service. Narrow the overview to introductory assessment and a first action; do not promise a full funding strategy or complete sustainability plan.

Use the 2018 guidebook's phase labels consistently if teaching that edition. The later toolkit uses different wording in some places. Identify the source/version rather than silently blending labels. Explain that phases support diagnosis and revisiting decisions; they are not a competition to achieve the highest score.

**Done when:** Each advertised outcome points to a taught example and an assessed learner output. The introduction is included in `config.yaml`. The final record includes resources even though there is no new standalone resources episode.

### 3. Replace the jump from definitions to expert judgment — P1

**Verified:** Governance names four models but gives no worked comparison. Community work begins with a blank stakeholder map. Infrastructure asks groups to select tools after lists of criteria, without a worked decision or enough scenario constraints.

**Teaching judgment:** Learners must simultaneously invent a project context, recall relevant people or tools, choose a representation, interpret criteria, negotiate with peers, and defend a conclusion. Much of this effort can go into guessing the task rather than learning the target decision skill.

**Change:** Provide completed and partial examples and a bounded choice for each major task. A short prediction or attempt may precede an example when the instructor explicitly connects responses to the explanation. Adjust support to demonstrated prior knowledge. Reuse one project so learners can concentrate on a new decision rather than rebuilding context. Supply a checkpoint copy of previous outputs so missing one activity does not block the rest.

**Done when:** No required task assumes knowledge of a learner's own project or of actual platform features. A learner without a leadership role can complete the core route.

### 4. Teach governance through decisions, not a menu of exclusive labels — P1

**Verified:** The current comparison puts founder authority, consensus, contribution-based influence, and foundation support side by side. Its text also associates consensus with voting without distinguishing their rules.

**Editorial concern:** These labels describe different dimensions. A foundation-supported project can also have maintainers who decide releases and a consensus process for strategy. A label alone does not tell a learner who can decide, how a disagreement ends, or what happens when the decision maker leaves.

**Change:** Start with one ordinary decision, then vary its consequences. Teach who proposes, who is consulted, who decides, where the reason is recorded, and who acts during absence. Put the four named models in a brief comparison/reference box after learners have a concrete decision to reason about. Explain that voting and consensus require specified procedures and are not synonyms.

**Done when:** Learners can write and defend an operational rule. They do not have to select a supposedly best model from a list.

### 5. Add feedback that distinguishes sound reasoning from plausible talk — P1

**Verified:** The three substantive episode sources contain no solution blocks or specific instructor guidance. Instructor notes and learner profiles are placeholders. A discussion can surface good ideas, but the materials do not say how to assess them or what to do after a misconception appears.

**Change:** Add a brief individual check before each main group activity. Give each check an explanation of the answer and the misconception behind alternatives. For open decisions, provide a sample answer plus criteria for acceptable alternatives. In instructor notes, specify an observable sign to pause and the explanation or practice to use next.

**Done when:** Another instructor can explain why an answer is adequate, identify an important error, and choose a response. Every learner produces some individual evidence; a confident group spokesperson cannot be the only evidence of understanding.

### 6. Reduce participation and presentation barriers — P1

**Verified:** Several apparent lists are published as paragraphs with literal hyphens: community groups, stakeholder types, mapping instructions, the infrastructure description, and scenario steps. The source often omits a blank line before the list. The map task offers arrows or color without a supplied legend or equivalent table.

**Change:** Fix list boundaries and check the rendered HTML. Offer the same assessment in a table or diagram, with identical criteria. Supply labels instead of relying on color. Begin discussion with silent writing; rotate recorder and reviewer roles. Make personal disclosure optional. Put activity inputs and instructions together. Avoid mandatory accounts, new diagram software, and live web research.

**Done when:** Lists render as lists, instructions are sequential, a text-only route is complete, and the required activities work from printed materials. This is a scoped improvement, not a claim of full accessibility compliance.

### 7. Budget learning and debrief time, then pilot — P1

**Verified:** Episode metadata totals 100 minutes: governance 20 teaching + 10 exercises, community 20 + 15, infrastructure 20 + 15. The instructor HTML shows 30, 35, and 35 minutes. The metadata does not establish whether open discussion and reporting fit those allocations.

**Change:** Use the schedule below as an initial design budget. Include reading, individual responses, group work, and feedback inside each allocation. Record actual times in the pilot. If time runs short, cut extra whole-class reports and optional model comparisons before cutting practice or feedback.

**Done when:** Timings agree across metadata, instructions, and instructor notes. No one reports the proposed timings as measured results.

## Proposed audience and finish line

**Working assumption:** Adults in libraries, research, or open scholarship who know what collaborative projects are but have little experience making explicit sustainability decisions. They may be contributors rather than decision makers. They need no coding, platform-administration, budget-management, or formal governance experience.

Create two short personas in `profiles/learner-profiles.md`: a contributor who wants to improve participation but cannot authorize changes, and a small-project maintainer facing limited time and an impending handover. State existing knowledge, goals, and support needs for each. These are design assumptions to check with actual participants.

**Finish line:** Given a short project brief, produce a concise decision record that connects a community need, a decision rule, an infrastructure choice, and the people and money needed to sustain it. Name an uncertainty and a practical next action. The result is a proposal to discuss with stakeholders, not permission to impose a new structure on them.

| Learning objective | Evidence the learner produces |
| --- | --- |
| Connect a sustainability risk to relevant ITAV facets, allowing overlap | A risk and explanation naming the affected facets |
| Distinguish a stated project fact from an assumption about community needs | One fact, one unknown, and a question for a named group |
| Draft a rule for a project decision and explain a tradeoff | A decision row with consultation, authority, record, and backup |
| Compare infrastructure options against needs and capacity | A choice justified by case evidence, with an alternative and limitation |
| Propose an achievable first action | An action, responsible role, consultation needed, and review point |

## Shared fictional case: Open Methods Kit

All names, capacities, and service profiles in this case are invented for teaching. They are not claims about real services, prices, or institutions.

Open Methods Kit publishes twelve openly licensed research-methods lessons and the source for its small website. Readers can reuse the public lessons without accounts. Educators send corrections by email because several do not use code-hosting tools. Two volunteers maintain the collection. Together they can sustain **two hours of maintenance each week** and **$25 per month** in service costs. The person who currently publishes updates will leave in six weeks. A second volunteer can edit text but has never published a change. The site works, but there is no documented rule for approving substantial changes or handling a maintainer's absence.

Decisions to practice: how to receive a correction; who approves a change that alters a lesson's meaning; what level of support can continue after the maintainer leaves; and how to preserve a citable release. The case does not establish what all educators want. Learners must identify one question to ask them.

The two-hour allowance covers maintenance work as a whole. Treat the service profiles below as estimates of routine technical work, not as allowances that already include editorial review, mentoring, or handover. Learners must identify those additional demands. If their duration is unknown, name the check needed; do not invent available capacity.

### A. Community activity: complete and question a starter table

Demonstrate one row aloud: educators who email corrections are present in the case; requiring a code-hosting account may create a barrier; whether they would use another submission channel remains unknown.

| Group | Evidence from the case | Need or barrier to investigate | How to ask or involve them |
| --- | --- | --- | --- |
| Educators submitting corrections | Some use email and do not use code-hosting tools | Can they submit and track a correction through the proposed route? | Ask an educator to try the draft instructions |
| Readers reusing a lesson | Public access without an account is required | Complete this cell | Complete this cell |
| Current and incoming maintainers | Complete this cell | Complete this cell | Complete this cell |

**Task:** Complete the table using brief phrases. Mark one statement as a fact or an assumption. Write one question that would test an assumption. Choose a group whose exclusion would change the publishing decision and explain why. A diagram is an optional equivalent, with labeled relationships.

**Feedback criteria:** Distinguish users from maintainers without assuming the categories are exclusive. Cite the case for a fact. Treat unconfirmed needs as questions. Suggest a concrete way to hear from the affected people. A neat diagram or long list of stakeholders is not evidence by itself.

**Checkpoint copy:** Provide a completed starter table for the next episode, so a learner can resume without finishing every cell.

### B. Governance activity: complete a decision rule

Show a worked example for correcting a broken link: a reader proposes the correction; the editor checks the destination; a maintainer publishes; a change note records the correction; the trained backup acts if the maintainer is unavailable. Explain why a low-consequence correction can use a simpler process than a change to a lesson's meaning.

**Task:** Complete a supplied row for a substantive lesson change. Include who can propose, whose input is needed, who decides, how the decision and reason are recorded, and how absence or unresolved disagreement is handled. Justify one tradeoff. Do not require a formal committee or legal structure.

**Sample acceptable response:** Anyone can propose a change. The editor seeks input from a lesson user and a maintainer. The designated content lead decides after considering that input and records the reason with the change. If the lead is absent, the named backup follows the same process. If the evidence is insufficient or a dispute remains unresolved, hold the substantive change for a stated review date while continuing routine corrections.

This answer is one possible design, not the official ITAV model. Other answers can pass if authority, participation, transparency, and continuity are clear and feasible for this small project. Consultation must have an actual path to affect the decision.

### C. Infrastructure activity: compare supplied service profiles

These are fictional alternatives. Learners should not browse vendor sites or rely on existing brand knowledge.

| Profile | Monthly service cost | Routine maintenance | Publishing and contributions | Continuity information |
| --- | --- | --- | --- | --- |
| A: managed publishing | $12 | About one hour/week | Public reading, web editor, corrections by email | Content export available; verify handover and account recovery |
| B: existing institutional service | No direct charge to the project | About two hours/week | Public reading; institutional accounts publish; outsiders can email corrections | Institutional support exists; next year's eligibility is unconfirmed |
| C: self-managed server | $8 | About six hours/week | Flexible access and custom workflows | Team handles updates, backups, and recovery; no trained backup |

First demonstrate rejecting C under the stated staffing constraint. Low service cost does not make it supportable. That is a demonstration, not the main exercise.

**Task:** Compare A and B. Choose a provisional option using two case facts. Identify an advantage of the other option. Name a continuity uncertainty and a check before committing. Explain how the chosen workflow will still accept corrections from educators who do not have publishing accounts.

**Sample answer:** A leaves more of the available maintenance time for content work and is within the cash limit. B may offer useful institutional support and saves the service fee, but its routine work uses the full current maintenance allowance. Before choosing A, test whether the incoming maintainer can publish and recover access, and check that exports can be used elsewhere. Before choosing B, confirm ongoing eligibility and support. Either can be defended if the response acknowledges its unresolved constraints.

**Feedback criteria:** Use the stated capacity and needs. Do not invent features. Separate a current fact from an uncertainty. Explain a real tradeoff. Popularity alone is insufficient justification.

### D. Short individual checks with diagnostic feedback

These replace the earlier weak multiple-choice examples. Use one short response before each main activity, after the relevant concept has been introduced. A short initial attempt can also be revisited after explanation. Ask learners to answer independently before discussion. Accept uncertainty and respond to the reasoning rather than rewarding polished wording.

1. **Community:** Several educators send corrections by email. State one supported fact and one claim about their preferences that the case does not establish. **Feedback:** Email is a channel currently used by some educators. The case does not establish that everyone prefers it, that no one could use another channel, or that a new forum is needed. Ask one affected educator to test a proposed route rather than treating an assumption as a requirement.
2. **Governance:** The team names the second volunteer as backup publisher. What missing evidence would you seek before calling this a workable handover? **Feedback:** Look for a demonstrated publishing task, suitable access and account recovery, time to take responsibility, and a clear decision rule. Learners need identify an important missing condition, not recite every item. A name alone does not establish capability.
3. **Infrastructure:** Profile B uses the full two-hour weekly maintenance allowance. Can it still absorb new correction requests? Explain what you can and cannot conclude. **Feedback:** There is no stated spare capacity for review. Learners should request an estimate or observation of review work and consider reducing scope, reallocating effort, or selecting another option. Do not assume free labor or reject the option without considering a changed support commitment.

For an incorrect or unsupported response, explain the specific gap and let the learner revise one sentence. For a sound response, change one condition rather than adding redundant scaffolding. These prompts are proposed checks, not validated measures of cognitive load or project health.

## Integration task and assessment

Assemble the earlier outputs into a one-page decision record. Supply headings and a partly completed version. Include:

1. The community need and the case evidence supporting it.
2. A governance rule for one consequential decision.
3. An infrastructure choice, a credible alternative, and a limitation.
4. The recurring labor and money required, one-off transition effort, and the stated boundary of support. Add a short note on the release to preserve and cite, its location, and its public maintenance status.
5. One uncertainty, a next action, a responsible role, who needs to be consulted, and a review date or event. State what observation would cause the team to reconsider the choice.

A well-justified handover, smaller scope, or responsible sunset may satisfy the task. Assess its fit to the evidence and effects on users. Do not require continued growth as the correct outcome.

Use a short checklist with **demonstrated / needs revision / not yet addressed**, without a numerical total. Give the learner one specific revision to make. State where different choices can still satisfy the criteria.

**Individual exit check:** The publishing maintainer must leave tomorrow rather than in six weeks. Name the first action you would change in your record, explain why, and identify another facet affected. This varies one fact while keeping the project familiar. Do not introduce a new kind of project at the last moment.

Optional transfer: learners identify one decision in their own project, who they must consult, and one limit to applying the case's solution. They may continue with the fictional case instead. A personal action plan is useful but is not evidence that a real project's stakeholders have approved it.

For an optional follow-up, provide one short changed-constraint case and ask learners first to recall the decision questions, then apply them with access to the worksheet. Pilot a one- to two-week interval as a practical choice, without claiming it is an established optimum. Separate the results from the immediate exit check and from any later evidence of workplace use. Providing this activity does not authorize sending or scheduling messages to participants.

## Proposed 120-minute pilot

| Segment | Total minutes | Teaching / exercises | Included work |
| --- | --- | --- | --- |
| Introduction | 10 | 8 / 2 | Purpose, shared case, four facets, brief baseline response |
| Community needs | 25 | 8 / 17 | Check, worked row, individual start, paired completion, feedback |
| Governance | 25 | 8 / 17 | Check, worked rule, paired adaptation, feedback |
| Break | 10 | Outside episode metadata | Rest |
| Infrastructure | 25 | 8 / 17 | Check, worked rejection, bounded comparison, feedback |
| Synthesis and exit | 25 | 3 / 22 | 3-minute orientation; 17-minute record/review/revision; 5-minute individual exit |
| **Total** | **120** | **35 / 75, plus 10-minute break** | Initial budget; not measured timing |

The check and feedback times are included in each episode, not added on. Instructor notes should subdivide the exercise allocations explicitly and allow a short transition within them. Limit whole-class reporting to contrasting examples rather than every group. If the intended audience is experienced maintainers, a shorter project clinic may be appropriate; that is a different teaching assumption and should be stated in the overview.

## File-by-file implementation backlog

Paths below exist in the reviewed snapshot unless marked **new**. They are repository-relative, not paths on Tim's laptop. Reconcile them with the current checkout.

| Priority | File | Required change |
| --- | --- | --- |
| P0 | `episodes/introduction.md` | Replace the excluded Markdown demonstration with case-based orientation and the four-facet model. |
| P0 | `config.yaml` | Include introduction; order introduction → community → governance → infrastructure → synthesis. List learner and instructor materials as appropriate to current Workbench conventions. Retain pre-alpha until the project's lifecycle criteria are met. |
| P0 | `index.md`, `README.md` | Align audience, prerequisites, scope, five observable outcomes, deliverable, and proposed duration. Make application beyond heritage OSS an explicit adaptation. |
| P0 | `episodes/governance.md` | Correct the Appendix A reference. Supply a local, attributed decision worksheet rather than an unsupported scoring procedure. |
| P0 | `episodes/infrastructure.md` | Supply scenario facts and fictional option profiles. Remove dependence on an absent list or outside tool knowledge. |
| P1 | `episodes/community-needs.md` | Add the worked row, starter table, fact/assumption distinction, question, check, feedback, and checkpoint. |
| P1 | `episodes/governance.md` | Add decision-rule practice, check, worked response, alternatives, and misconception notes; move model labels into reference context. |
| P1 | `episodes/infrastructure.md` | Teach the worked rejection and A/B comparison; add check, feedback, capacity constraints, and continuity question. |
| P1 | `episodes/synthesis.md` **new** | Add final record, qualitative checklist, one-fact variation, and optional own-project transfer. |
| P1 | `learners/project-worksheet.md` **new** | Provide case, starter tables, option profiles, and decision-record headings in an accessible print-friendly form. Ensure it renders and is reachable. Use the repository's supported asset approach if the learner section cannot host it. |
| P1 | `learners/setup.md` | Explain materials and worksheet access, print/text options, optional project choice, and that no software installation or account is required. |
| P1 | `learners/reference.md` | Supply concise definitions, an accurate ITAV source/version note, official links, and clearly attributed adaptations. |
| P1 | `profiles/learner-profiles.md` | Replace the placeholder with the two design personas and their assumptions. |
| P1 | `instructors/instructor-notes.md` | Replace the placeholder with schedule, facilitation, response patterns, checkpoints, cut points, and pilot plan. Add inline instructor blocks near relevant activities. |
| P1 | All edited learner sources | Fix list spacing, clear action order, link text, and heading/callout hierarchy. Avoid duplicate exercise labels created by redundant headings. |
| P2 | Reference or instructor materials | Optional mature-project variation, extra practice, and a longer resources/funding module only after the core pilot shows a need. |

Keep source maintenance proportionate. Reuse existing Workbench features; do not build an application, introduce an automatic grader, redesign the theme, or add a new document-generation toolchain for these worksheets. Have one canonical copy of case facts and profile values; use the build system's supported inclusion mechanism if practical, or keep the full data in the worksheet and link to it from episodes. Ensure the all-in-one lesson remains usable with that linked handout.

## Validation and definition of done

### Build and rendering

1. Use repository instructions and its installed Workbench version. The current template mentions `sandpaper::check_lesson()` and `sandpaper::build_lesson()`; confirm those are appropriate locally before running them. Run applicable validation and build without deployment.
2. Inspect the rendered summary, each episode, learner and instructor all-in-one views, reference, and worksheet. Confirm the intended order, lists, links, timing, and print/text access.
3. Confirm solution blocks reveal sample reasoning and instructor-only material appears in the intended view. Validate colon-fenced block nesting using the repository's conventions.
4. Check that every referenced worksheet, table, profile, and checkpoint exists. Validate local links and anchors. Check official external links without making live vendor comparisons part of the lesson.
5. Review `git diff` for unintended edits, generated output, stale transitions, and scope drift. Report build failures honestly. A successful build checks structure; it does not establish teachability.

### Instructional review

- Each objective has taught preparation, required practice, and a clear way to assess the result.
- Each major decision has adequate preparation, a visible example of reasoning, and feedback. A bounded attempt can precede explanation when followed by consolidation; independent full-task performance is assessed after preparation.
- Every core task can be completed from supplied case facts and materials.
- Each major exercise states its input, output, time, working arrangement, and feedback criteria.
- Open questions have acceptable alternatives; checks have diagnostic explanations.
- Individual responses provide evidence beyond group reporting.
- Resources, phase differences across facets, and change over time are visible without adding a full funding curriculum.
- Scope and timing are consistent. Nothing claims that sustainability, equity, or community approval has been achieved by completing a worksheet.

### Human pilot, required before claiming success

Run a small pilot with people resembling the intended learners and, if possible, a second instructor observing. Ask the observer to note where learners stop, ask what a prompt means, invent unsupported facts, or wait for the most experienced person. Record actual exercise and debrief times. Assess the final individual responses against the stated criteria and keep examples of both adequate and incomplete reasoning with permission. If participants choose to complete the optional follow-up, record delayed recall and application separately. Test workplace use through a concrete later action, such as consultation or a demonstrated handover, without treating training as authority to change project governance.

Ask participants what was confusing and useful, but assess learning from their decisions and explanations as well. Revise the largest observed obstacle first. If learners already reason fluently and mainly need facilitated planning time, narrow the audience and recast the lesson as a project clinic rather than adding unnecessary beginner scaffolding.

## Source notes

- [Published learner lesson](https://www.tim-dennis.com/sustainable-open-projects/aio.html), [summary/setup](https://www.tim-dennis.com/sustainable-open-projects/), and [instructor all-in-one](https://www.tim-dennis.com/sustainable-open-projects/instructor/aio.html): inspected directly on the review date.
- [Pinned repository snapshot](https://github.com/jt14den/sustainable-open-projects/tree/234a050c2507e290b1614a544939ad38e7f628b1): primary evidence for source defects and the implementation paths.
- Greg Wilson, [Teaching Tech Together](https://teachtogether.tech/en/index.html): focused chapters listed above; pedagogical framework, not a classroom evaluation of this lesson.
- LYRASIS, [2018 guidebook](https://itav.lyrasis.org/wp-content/uploads/2024/10/ITAV_Report_Interactive.pdf): especially printed pages 8–10 on facets/phases and printed page 41 on Appendix A. The PDF's file path contains a later upload date; the publication identifies itself as February 2018.
- [Current ITAV toolkit](https://itav.lyrasis.org/toolkit/), [governance activities](https://itav.lyrasis.org/toolkit-governance/), and [kickoff resources](https://itav.lyrasis.org/itav-kickoff-activity-and-resources/): official context for appropriate activity selection and attribution. The proposed lesson is an introduction, not a substitute for a full ITAV analysis.

## Research update: concepts and the UC OSPO playbook

Updated 25 November 2026. This section and the revised examples incorporate follow-up research. Where they qualify an earlier recommendation, use the updated version.

**Recommendation:** Keep ITAV as the lesson's organizing framework. Use the UC OSPO playbook for academic context, practical references, and short cases. Update both the sustainability concepts and the teaching design. A second full framework would add more vocabulary than this introductory workshop needs.

This was a targeted review of research papers and official project guidance, not a systematic review. I checked original publication pages, accessible article text, and the playbook source. The research does not directly test this lesson or this audience.

### A. What the playbook contributes

Reviewed repository snapshot: [`563615951611866b1822b20a313091fa42d8077e`](https://github.com/UC-OSPO-Network/playbook/tree/563615951611866b1822b20a313091fa42d8077e). The introduction explicitly describes its organization as inspired by ITAV. Its categories are an academic adaptation, not ITAV's original four facet names.

| UC OSPO playbook category | Connections to ITAV | Use in this lesson |
| --- | --- | --- |
| Discoverability | Technology and Community Engagement; Governance where responsibilities and reuse terms matter | Identify what someone needs to find, understand, cite, and reuse a specific release. |
| Funding | Resources and Governance | Distinguish cash, staff effort, institutional support, and who can authorize a commitment. |
| Community | Community Engagement and Governance | Choose participation and support arrangements that fit users and maintainer capacity. |
| Product design | Technology and Community Engagement; Resources for maintenance and review effort | Ask how design enables contributions and what accepting them costs. |

This is an editorial crosswalk of related questions, not a one-to-one equivalence or a new validated model. Keep it in instructor notes and the reference page. Learners can continue using ITAV's four facets throughout the core activities.

The most useful developed material is the [scholarly preservation chapter](https://github.com/UC-OSPO-Network/playbook/blob/563615951611866b1822b20a313091fa42d8077e/facet1/scholarly_preservation.md), [funding introduction](https://github.com/UC-OSPO-Network/playbook/blob/563615951611866b1822b20a313091fa42d8077e/facet2/funding_intro.md), [community introduction](https://github.com/UC-OSPO-Network/playbook/blob/563615951611866b1822b20a313091fa42d8077e/facet3/community_intro.md), and [communication chapter](https://github.com/UC-OSPO-Network/playbook/blob/563615951611866b1822b20a313091fa42d8077e/facet3/communication.md). Link selected sections at the point of use; do not assign the whole playbook as prerequisite reading.

**Readiness limits — strong direct evidence:** The playbook's landing page describes a demonstration with unfinished pages. At this snapshot, governance, project management, open-codebase design, and contribution-design pages have headings but no substantive guidance. The documentation page is also only a heading. Communication has unresolved `AAQ` markers. A heading in the table of contents is not a completed teaching resource. Recheck these pages before the next lesson release.

The playbook also states that its descriptions of campus workflows are educational guidance, not approved campus policy. Teach participants to identify a question and the appropriate local office. Do not turn a paragraph in the playbook into a universal rule about UC ownership, funding acceptance, or licensing.

### B. Sustainability concepts to update

**1. Make time and institutional support explicit resources.** The 2026 UC survey by Scarlett and colleagues received 294 valid responses. Lack of time, especially documentation time, was prominent; respondents also prioritized computing environments and sustainability grants. Recruitment was uneven across campuses and was not a representative probability sample. The authors note that the survey did not offer protected time as a proposed support option. It cannot establish that grants are preferable to workload allocation. [R1]

**Evidence:** Moderate for choosing topics relevant to UC contributors: direct, local empirical evidence with sampling limits. It does not establish the effect of any intervention.

**Lesson change:** Every proposal must identify recurring work, one-off transition work, an available role, and what will be deferred or supported institutionally. A backup name is insufficient if that person lacks time, access, or skills. Do not imply that better personal habits resolve an unfunded institutional responsibility.

**2. Define support boundaries and contribution capacity.** The playbook distinguishes publishing software, supporting users, and accepting outside contributions; it explicitly accepts a publish-only project as legitimate. CHAOSS warns that new contributions also create review and onboarding work. [R2]

**Lesson change:** Ask, “What are we offering to users, and what are we able to maintain?” Accept a limited support policy when clearly communicated and appropriate to the case. Treat the playbook's participation levels as choices that can change, not a compulsory maturity ladder. Do not equate community with a reserve of free labor.

**3. Include preservation and responsible endings in sustainability.** The playbook treats citation, succession, and archival together. CHAOSS explicitly treats a planned sunset as a legitimate lifecycle outcome. [R3]

**Lesson change:** A sound response to the departing maintainer may involve a handover, a smaller support commitment, institutional adoption, or an orderly sunset. Require evidence and attention to affected users. Do not build the rubric around keeping every project growing indefinitely. These concerns already existed in ITAV; their absence from the lesson is a coverage gap, not proof that the framework is obsolete.

**4. Separate citation, preservation, and operation.** GitHub's archive setting makes a repository read-only. Zenodo's preservation policy concerns retained files and explicitly does not promise continued usability or understandability. [R4–R5]

**Lesson change:** A DOI, an archived repository, and an operating service solve different problems. Ask who preserves the release and who, if anyone, continues support and operation. Do not repeat an assumed universal repository-retention period or promise that a stored release will remain runnable. A simple citation and preservation plan belongs in the final record; identifier implementation can remain follow-up material.

The [FAIR4RS Principles](https://doi.org/10.1038/s41597-022-01710-x), published in 2022, add useful research-software guidance on version identification, metadata, provenance, and reuse. [R15] Use them as a reference behind the preservation task. They do not replace ITAV's questions about people, authority, and resources. The core task can ask whether a future researcher could identify the exact release and understand its reuse conditions; it need not introduce another acronym or a complete FAIR assessment.

**5. Use evidence to investigate health, not to award a universal score.** CHAOSS recommends interpreting metrics with project goals and people who understand the work. It cautions against decontextualized comparisons and measures that can punish individuals. [R6]

**Lesson change:** Add one contextual question to the decision record: what observation would make us reconsider this choice? Examples include a backup completing a release, an educator successfully submitting a correction, or review work exceeding available time. A quiet repository is not automatically unhealthy. No dashboard, contributor ranking, or fixed activity threshold is required.

**6. Treat governance as authority, participation, and continuity.** Keep the earlier decision-rule revision. The playbook's governance chapter cannot yet fill this teaching gap. Use explicit examples of who decides, whose input changes a proposal, who records reasons, and what happens during absence. Include a reachable conduct-reporting and response route when discussing community policy. Posting a policy alone does not demonstrate that someone can act on it.

The playbook's funding and licensing chapters can support an advanced route. The core workshop should help learners identify missing information and seek appropriate advice, without becoming a license-selection or grants-administration course. CHAOSS's viability guide also supports checking dependencies and maintenance responsibilities, but it is primarily written for organizations consuming software; adapt its questions rather than importing its entire metric model. [R7]

### C. Teaching concepts to qualify

**1. Cognitive load is a design hypothesis, not a diagnosis from page length.** A 2022 review of computing education research documents confusion between versions of cognitive load theory. A later experimental paper also describes the unresolved distinction between two- and three-component accounts. “Germane load” is not an independently agreed quantity to add to or subtract from a teaching budget. [R8–R9]

**Change:** Say that a prompt requires several unfamiliar decisions at once, and name them. Check that hypothesis against learner explanations, errors, and observations. Do not claim to have measured overload from reading the lesson. Keep theory vocabulary in instructor notes. Maintain captions, readable text, and access options; a simplistic rule against redundant information is not an accessibility policy.

**2. A worked example need not be the first thing learners ever do.** Sinha and Kapur's 2021 meta-analysis finds benefits for some problem-solving-before-instruction designs, with important design and learner conditions. It does not validate unsupported discovery or establish that problem-first instruction is best for an academic governance workshop. [R10]

**Change:** Keep a guided default for major tasks. Permit a short, bounded prediction or attempt before the explanation, then explicitly compare responses and consolidate the idea. Avoid absolute claims that any struggle is harmful or any failure is productive. An experienced maintainer can attempt the decision with less scaffolding, using the same output criteria.

**3. Show reasoning and competing acceptable answers.** A 2025 systematic review finds that learning from erroneous examples depends on the prompts, explanations, and prior knowledge; benefits are not uniform. [R11]

**Change:** Demonstrate why a decision fits the available evidence, what assumption it makes, and when the alternative would be better. Add one flawed decision for learners to repair after they have seen a sound example. In governance, do not present a local value judgment as the only correct answer. The three original sample checks were also too easy and all used the same answer position; their replacements below ask for evidence and explanations.

**4. Retain integration while varying the problem.** The official 4C/ID model organizes complex learning around whole tasks with support for reasoning and procedures. This supports considering an integrated task structure; it is not evidence that this particular short workshop implements or validates the full model. [R12]

**Change:** Keep the shared decision record visible from the start. At the end, vary one condition and ask learners to revise their reasoning. Offer a brief second-case comparison during a longer version or optional follow-up so participants can identify what does and does not generalize. Do not add an unfamiliar domain only at the final assessment.

**5. Distinguish immediate completion, retention, and use at work.** Retrieval-practice reviews support benefits across multiple classroom settings. A meta-analysis published in October 2026 emphasizes conditions and context; its population is primary and secondary education, not adult OSPO workshops. [R13–R14]

**Change:** Keep the individual exit response. Provide an optional short follow-up task after the workshop: recall the decision questions, then apply them to one changed constraint using the worksheet if needed. A one- to two-week interval is a practical pilot choice, not an experimentally established optimum for this lesson. Assess workplace use separately: whether someone consulted the right people or tested a handover, rather than whether they liked the session.

### D. Use the interviews as cases, with limits

Two developed playbook interviews offer useful contrasts:

- [Jonathan Balkind / OpenPiton](https://github.com/UC-OSPO-Network/playbook/blob/563615951611866b1822b20a313091fa42d8077e/interviews/jon_balkind.md) describes user support, reusable examples, and contributions that never become merged code. Use a short paraphrase to ask what counts as a contribution and which support demands the project can absorb.
- [Juan Cobo Betancourt / Neogranadina](https://github.com/UC-OSPO-Network/playbook/blob/563615951611866b1822b20a313091fa42d8077e/interviews/juan_cobo_betancourt.md) connects community trust, institutional arrangements, modular tools, and non-code contributions. Ask how community needs change a technical or organizational decision.

These are reported experiences, not comparative tests of success. Do not generalize from them that every maintainer should answer every message, start a nonprofit, create a forum, or run regular meetings. Let learners name a condition under which the described approach would be unsuitable. Keep real interview facts separate from any fictional teaching constraints.

Apply the same editorial care to the playbook itself. Counting how many metric categories concern community cannot establish that community matters more than funding or technical quality. The communication chapter's preferences for meetings should not become a universal rule; accessibility, time zones, documentation, and available effort can favor asynchronous work. These are reasons to teach context, not reasons to discard the playbook.

### E. Codex implementation changes from this research

Apply these within the existing episode sequence and time budget. Replace weak material and optional reporting before adding more minutes.

| File or activity | Research-driven change | Acceptance check |
| --- | --- | --- |
| Introduction and instructor notes | Identify ITAV as the organizing framework and the playbook as the academic companion. Keep the crosswalk in reference material. | Learners are not asked to memorize eight facet labels. |
| Community needs | Add an explicit choice of support and contribution boundaries; account for review work. | A small, bounded support model can be defended without being marked immature. |
| Governance | Test authority and the backup's actual capability; permit proportionate response procedures. | A named backup without access, skill, or time is identified as incomplete. |
| Infrastructure | Distinguish running costs, maintenance, review, and one-off handover work; include dependence on external services. | The preferred option must fit the whole proposed workflow, not only hosting fees. |
| Synthesis and worksheet | Add a compact public status/citation/preservation note and a reconsideration trigger. Permit justified handover, reduced scope, or sunset. | Archiving files is never presented as continued operation or support. |
| Reference | Add selected playbook sections, the UC survey, and a short annotated teaching bibliography. | Placeholder pages are not required reading; sources have access dates or pinned commits. |
| Checks and instructor notes | Replace the weak sample checks; allow bounded attempts before explanation; vary support with prior knowledge. | Each response requires a case fact or a defensible reason. |
| Pilot notes | Separate completion, individual reasoning, delayed recall/application, and workplace action. | Report evidence actually collected and do not label a simple satisfaction question a learning measure. |

### F. Research sources and strength

The annotations distinguish empirical evidence, design frameworks, and practitioner guidance. No source establishes the effectiveness of the proposed lesson. Accessed 25 November 2026.

| ID | Source | Contribution and limit |
| --- | --- | --- |
| R1 | Scarlett et al. (2026), [A system-wide snapshot](https://doi.org/10.1371/journal.pone.0348894) | Peer-reviewed UC survey. Moderate evidence for local priorities; uneven recruitment and self-report limit generalization and causal interpretation. |
| R2 | CHAOSS, [Contributor Sustainability](https://www.chaoss.community/practitioner-guide-contributor-sustainability/) | Practitioner guidance on workload, contributions beyond code, and succession. Strong evidence of current CHAOSS recommendations; limited evidence for effects of a particular intervention. |
| R3 | CHAOSS, [Sunsetting an Open Source Project](https://www.chaoss.community/practitioner-guide-sunset/) | Current guidance on transition and responsible endings, including stable projects with little activity. Operational advice, not a tested universal decision rule. |
| R4 | GitHub Docs, [Archiving repositories](https://docs.github.com/en/repositories/archiving-a-github-repository/archiving-repositories) | Strong primary documentation of what GitHub's archive operation does. It is not a preservation certification. |
| R5 | Zenodo, [General Policies](https://about.zenodo.org/policies/) | Strong evidence of the repository's stated commitments and limits. Retaining objects does not promise continued functional usability. |
| R6 | CHAOSS, [Interpreting Metrics](https://www.chaoss.community/practitioner-guide-introduction/) | Context-sensitive assessment guidance. Supports cautious interpretation, not a universal project-health score. |
| R7 | CHAOSS, [Assessing Viability](https://www.chaoss.community/practitioner-guide-viability/) | Guidance for software consumers; includes security, dependencies, governance, community, and strategy. Scope differs from a maintainer workshop. |
| R8 | Duran, Zavgorodniaia, and Sorva (2022), [Cognitive Load Theory in Computing Education Research: A Review](https://doi.org/10.1145/3483843) | Peer-reviewed mapping review. Publication metadata and author-hosted abstract were verified through [Aalto](https://research.aalto.fi/en/publications/cognitive-load-theory-in-computing-education-research-a-review/); publisher full-text access failed. Used for its reported methodological cautions, not uninspected detailed findings. |
| R9 | [The Distorting Influence of Primacy Effects on Reporting Cognitive Load in Learning Materials of Varying Complexity](https://doi.org/10.1007/s10648-024-09980-0) | Accessible experimental paper; describes contested load constructs and studies rating effects. Supports measurement caution. Its learning materials differ from project planning. |
| R10 | Sinha and Kapur (2021), [When Problem Solving Followed by Instruction Works](https://doi.org/10.3102/00346543211019105) | Meta-analysis of instructional sequencing. Moderate support for conditional problem-first designs; limited direct transfer to this workshop. |
| R11 | Dieterich, Rumann, and Rodemer (2025), [Conditions for Effective Learning from Erroneous Examples](https://doi.org/10.1007/s10648-025-10071-x) | Systematic review with mixed conditions and outcomes. Supports carefully explained comparisons, not indiscriminate error-first teaching. |
| R12 | 4C/ID authors' site, [The model](https://www.4cid.org/about/) | Primary description of whole-task instructional design; references the 2024 fourth edition of *Ten Steps to Complex Learning*. A design rationale, not an outcome estimate for this lesson. |
| R13 | Agarwal, Nunes, and Blunt (2021), [Retrieval Practice Consistently Benefits Student Learning](https://doi.org/10.1007/s10648-021-09595-9) | Systematic review of classroom experiments; [author-hosted full text](https://pdf.poojaagarwal.com/Agarwal_etal_2021_EDPR.pdf) available. Strong broader evidence for retrieval practice, with important geographic and task limits. |
| R14 | Ruitenburg et al. (2026), [Effectiveness and Boundary Conditions of Retrieval, Distributed, and Interleaved Practice](https://doi.org/10.1007/s10648-026-10225-5) | Published 29 October 2026. Meta-analysis of school classrooms. Useful update on boundary conditions; adult workshop retention and workplace transfer remain untested here. |
| R15 | Barker et al. (2022), [Introducing the FAIR Principles for research software](https://doi.org/10.1038/s41597-022-01710-x) | Primary community-principles paper. Strong evidence of the stated FAIR4RS principles; it does not establish that FAIR practices alone fund or sustain a project. |

**Keep in reserve:** Detailed license compatibility, commercialization routes, quantitative community analytics, and AI-specific contribution policies. These may warrant separate lessons. The current evidence supports making basic stewardship and capacity decisions more explicit first; adding every contemporary topic would work against this lesson's introductory purpose.
