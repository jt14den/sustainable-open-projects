# Local revision checks

Review date: 25 November 2026. Branch: `codex/teachability-workshop`.

## Scope and choices

The revised research brief is saved as `sustainable-open-projects-teachability-review.md`. P0 and P1 changes use a proposed 120-minute introductory workshop. ITAV remains the organizing framework; the UC OSPO playbook supplies optional academic context. Required work uses the fictional Open Methods Kit case and supplied service profiles. The worksheet is the canonical source for case facts and service values.

Changed lesson sources: `config.yaml`, `index.md`, `README.md`, `CITATION.cff`, all four existing episodes, new `episodes/synthesis.md`, learner setup and reference, new `learners/project-worksheet.md`, learner profiles, and instructor notes. The citation's invalid optional `type: lesson` field was removed after schema validation failed. Its abstract now matches the introductory scope. Contact uses the existing maintainer address; creation date matches the first Git commit, 24 April 2025.

The initial validation was local only. Tim subsequently authorized committing this revision, pushing its branch, and opening a pull request for build review. Generated site output remains ignored; the playbook repository is unchanged.

## Checks

| Check | Result |
| --- | --- |
| `wbcheck check . --fail-on warning --json` | Pass: no errors or warnings. Informational WB006 retains pre-alpha; WB105 flags the intentional 10-minute introduction. |
| `sandpaper::check_lesson()` | Completed; identifies this as an overview lesson and skips its episode checks. This is not a substitute for the other checks. |
| `sandpaper::validate_lesson()` | Passed fenced-div and internal-link/image validation. |
| `sandpaper::build_lesson(preview = FALSE)` | Generated learner and instructor pages and both all-in-one views successfully. |
| `cffr::cff_validate("CITATION.cff")` | TRUE after the optional invalid type was removed. |
| Generated HTML inspection | Confirmed sequence, lists/tables, worksheet links, valid solution-control targets, and instructor-only note placement. Setup renders within the summary page at `index.html#setup`, not as a separate `setup.html`. |
| Local paths and anchors | No broken main-content local paths or anchors across generated HTML. |
| Timing | 35 teaching + 75 exercises + 10 break = 120 minutes. Activity subdivisions agree with instructor notes. |
| `git diff --check` | Passed. |
| Visual browser/print inspection | Not completed: the local browser tool timed out on two attempts; the local preview server also reported a sandbox bind denial. HTML structure inspection is not visual or print-layout verification. |

The installed build reports a CRAN index connection warning, a locale warning, and Pandoc math-option deprecation warnings. These did not prevent generation. No dependency upgrades were made.

The current playbook governance, project-management, codebase-design, and contribution-design files were fetched on the review date and still contain headings without substantive procedures. Required exercises do not depend on them. References retain the reviewed pinned commit and distinguish source findings from teaching proposals.

## Human checks still required

Open `site/docs/index.html`, each episode, `project-worksheet.html`, `reference.html`, `aio.html`, and `instructor/aio.html` in a browser. Check layout, expand solutions, follow worksheet links, and print the worksheet with learner instructions. Perform visual and keyboard checks before teaching; this revision does not claim a full accessibility audit.

Pilot with a small group resembling the learner profiles and an observer if possible. Use the instructor notes to record actual activity and feedback times, unsupported assumptions, requests for clarification, and individual exit reasoning. Assess completion separately from reasoning. Obtain permission before retaining examples. Revise the largest observed obstacle first.

Optionally offer the changed-budget follow-up one or two weeks later, separating unaided recall from supported application. That interval is a practical choice, not a validated optimum. Check workplace actions separately. Neither build success nor worksheet completion establishes improved learning, retention, institutional approval, or sustainability.
