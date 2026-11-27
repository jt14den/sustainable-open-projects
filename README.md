# Sustaining Open Projects with the It Takes a Village Framework

## Lesson overview

Practice sustainability decisions for Open Methods Kit, a fictional open lesson collection. Use ITAV's four facets throughout, with selected UC OSPO Sustainability Playbook chapters as academic context. Applying heritage open source software guidance to other open projects is an explicit teaching adaptation.

The proposed introductory workshop takes **120 minutes**, including a 10-minute break. Timings are a pilot budget, not measured results. The lesson remains pre-alpha.

The finish line is a concise decision record connecting a community need, an operational decision rule, infrastructure, and resources. Include support limits, recurring and transition work, a citation/preservation/status note, and a first action to discuss with stakeholders. Handover, reduced scope, or responsible sunset can be justified outcomes. This workshop does not produce a full funding strategy or authorize changes to a real project.

## Outcomes and evidence

| After the workshop, learners can | Required evidence |
| --- | --- |
| Connect a sustainability risk to overlapping ITAV facets | Baseline risk and final explanation, with phase evidence and uncertainty |
| Distinguish facts from assumptions about community needs | Community table, question for an affected group, and support boundary |
| Draft and defend an operational decision rule | Governance row and tradeoff, with a capability check for the backup |
| Compare infrastructure within available capacity | A/B comparison including alternative, limitations, recurring work, and transition work |
| Propose an achievable first action | Final record with responsible role, consultation, review event, and reconsideration trigger; individual changed-deadline response |

## Audience and materials

For adults in libraries, research, and open scholarship who know collaborative work but have little experience making explicit sustainability decisions. Contributors need no authority to approve changes. No coding, administration, budget-management, or formal governance experience is required.

Use the supplied fictional case for every required task. Application to your own project is optional. Paper or a plain text document is enough; no new accounts, installation, or live research are required.

## Teaching and local validation

The sequence is introduction, community, governance, infrastructure, and synthesis. Use [setup](learners/setup.md), the [worksheet](learners/project-worksheet.md), and [instructor notes](instructors/instructor-notes.md). The notes contain the schedule, feedback responses, and human pilot protocol.

Run these from the repository root with the installed Workbench environment:

```sh
wbcheck check . --json
Rscript -e 'sandpaper::check_lesson(); sandpaper::validate_lesson(); sandpaper::build_lesson(preview = FALSE)'
```

Inspect the rendered learner and instructor pages and all-in-one views. Mechanical checks and a successful build do not establish learning or timing. Keep source edits separate from generated files in `site/`.

## Credit, maintenance, and license

This lesson draws on LYRASIS's February 2018 *It Takes a Village: Open Source Software Sustainability* guidebook, developed with IMLS support. The fictional case and decision worksheets are lesson adaptations, not official ITAV instruments. Selected UC OSPO Sustainability Playbook chapters provide academic context. See the [reference page](learners/reference.md) for source versions and limits.

Maintainer: Tim Dennis (tdennis@library.ucla.edu).
Lesson content: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [contributing guidance](CONTRIBUTING.md).
