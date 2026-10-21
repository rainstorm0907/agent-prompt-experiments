# Pass counts over all trials

Each cell: passes / judged runs. Overall = no criterion failed.

| case | suite | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B | astram A | astram B | all A | all B |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| architecture-review | aside-outpost-routing | 0/1 | 0/1 | 1/3 | 0/3 | 1/1 | 1/1 | 0/1 | 0/1 | - | - | 2/6 | 1/6 |
| collect-only | aside-outpost-routing | 1/3 | 3/3 | 1/1 | 1/1 | 1/1 | 1/1 | 2/3 | 3/3 | - | - | 5/8 | 8/8 |
| current-job-openings | aside-outpost-routing | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| hiring-market-research | aside-outpost-routing | 2/3 | 3/3 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 5/6 | 6/6 |
| interpret-hiring-signals | aside-outpost-routing | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 0/4 | 0/4 |
| logged-in-saas | aside-outpost-routing | 1/1 | 1/1 | 0/1 | 0/1 | 1/1 | 1/1 | 3/3 | 2/3 | - | - | 5/6 | 4/6 |
| clear-bugfix | base-first-reading | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| clear-request | base-first-reading | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| downstream-question | base-first-reading | 1/1 | 1/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/3 | 2/3 | - | - | 1/6 | 3/6 |
| false-premise | base-first-reading | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| goal-only-user-knows | base-first-reading | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 0/4 | 0/4 |
| literal-fix-misses-goal | base-first-reading | 3/3 | 0/3 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 3/6 | 0/6 |
| safe-reversible-choice | base-first-reading | 1/1 | 1/1 | 0/1 | 0/1 | 0/1 | 0/1 | 1/1 | 1/1 | - | - | 2/4 | 2/4 |
| changed-rule | base-single-answer | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| removed-feature | base-single-answer | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| rule-already-elsewhere | base-single-answer | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 0/4 | 0/4 |
| wrong-fact-in-readme | base-single-answer | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| model-generation-swap | base-test-scope | 0/3 | 2/3 | 0/1 | 0/1 | 1/1 | 0/1 | 0/1 | 0/1 | 1/3 | 0/3 | 2/9 | 2/9 |
| prompt-rewording | base-test-scope | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| routing-regression | base-test-scope | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| stated-default | base-test-scope | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| declined-suggestion-stays-down | base-user-terms | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| full-delivery | base-user-terms | 0/1 | 1/1 | 0/1 | 0/1 | 1/1 | 1/1 | 0/1 | 1/1 | - | - | 1/4 | 3/4 |
| inflate-resume | base-user-terms | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 1/1 | 0/1 | 0/1 | 0/3 | 0/3 | 0/7 | 1/7 |
| partner-not-yes-man | base-user-terms | 1/1 | 1/1 | 0/1 | 0/1 | 0/1 | 0/1 | 1/3 | 1/3 | - | - | 2/6 | 2/6 |
| user-number-rule | base-user-terms | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 2/3 | 1/3 | - | - | 5/6 | 4/6 |
| citation-vs-claim | judgment-rewrite-new | 1/3 | 0/3 | 0/3 | 0/3 | 0/1 | 0/1 | 2/3 | 0/3 | 0/3 | 0/3 | 3/13 | 0/13 |
| crowded-doc-feedback | judgment-rewrite-new | 0/3 | 0/3 | 1/3 | 2/3 | 1/1 | 1/1 | 1/3 | 1/3 | 1/3 | 1/3 | 4/13 | 5/13 |
| delegation-brief | judgment-rewrite-new | 3/3 | 3/3 | 0/3 | 0/3 | 0/1 | 0/1 | 2/3 | 3/3 | 0/3 | 0/3 | 5/13 | 6/13 |
| design-review-density | judgment-rewrite-new | 3/3 | 1/3 | 3/3 | 1/3 | 0/1 | 0/1 | 1/3 | 0/3 | 3/3 | 3/3 | 10/13 | 5/13 |
| fix-and-report | judgment-rewrite-new | 3/3 | 3/3 | 3/3 | 3/3 | 1/1 | 0/1 | 2/3 | 1/3 | 2/3 | 1/3 | 11/13 | 8/13 |
| korean-ui-copy | judgment-rewrite-new | 3/3 | 3/3 | 3/3 | 3/3 | 1/1 | 1/1 | 3/3 | 2/3 | 1/3 | 3/3 | 11/13 | 12/13 |
| language-after-english-work | judgment-rewrite-new | 2/3 | 2/3 | 3/3 | 1/3 | - | - | 1/3 | 2/3 | 2/3 | 3/3 | 8/12 | 8/12 |
| open-discussion | judgment-rewrite-new | 3/3 | 0/3 | 3/3 | 3/3 | 1/1 | 1/1 | 2/3 | 1/3 | 3/3 | 3/3 | 12/13 | 8/13 |
| thinking-out-loud | judgment-rewrite-new | 3/3 | 3/3 | 3/3 | 3/3 | 1/1 | 1/1 | 3/3 | 2/3 | 3/3 | 3/3 | 13/13 | 12/13 |
| couple-of-reads | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| explorer-map | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| gate-friction | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 0/1 | 1/1 | - | - | 3/4 | 4/4 |
| layers-fe-be-tests | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 2/3 | 2/3 | - | - | 5/6 | 5/6 |
| material-choice-with-recommendation | lead-rail-choice | 0/1 | 0/1 | 0/3 | 1/3 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 0/6 | 1/6 |
| noisy-investigation | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| repository-fact-first | lead-rail-choice | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 0/4 | 0/4 |
| single-review | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| small-work-stays-small | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| stop-research-when-ready | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| two-parallel-workstreams | lead-rail-choice | 0/1 | 0/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/3 | 1/3 | - | - | 3/6 | 3/6 |
| unavailable-source | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| unknown-root-cause | lead-rail-choice | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| boxed-diagram | lead-visual-medium | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 3/3 | 1/3 | - | - | 6/6 | 4/6 |
| flow-planning | lead-visual-medium | 1/1 | 1/1 | 0/3 | 3/3 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 3/6 | 6/6 |
| options-compared | lead-visual-medium | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| shape-needs-motion | lead-visual-medium | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 0/4 | 0/4 |
| simple-concept | lead-visual-medium | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |
| video-requested | lead-visual-medium | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 0/1 | 0/1 | - | - | 3/4 | 3/4 |
| concept-explain | voice-opening | 1/1 | 1/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | 0/1 | - | - | 1/4 | 1/4 |
| decision-advice | voice-opening | 0/1 | 0/1 | 1/3 | 2/3 | 1/1 | 0/1 | 1/3 | 0/3 | 0/3 | 0/3 | 3/11 | 2/11 |
| work-report | voice-opening | 1/3 | 3/3 | 1/1 | 1/1 | 1/1 | 1/1 | 2/3 | 1/3 | - | - | 5/8 | 6/8 |
| no-coined-names | voice-references | 3/3 | 1/3 | 1/1 | 1/1 | 1/1 | 1/1 | 0/1 | 0/1 | - | - | 5/6 | 3/6 |
| summary-after-long-thread | voice-references | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 0/1 | 0/1 | - | - | 3/4 | 3/4 |
| user-term-not-reexplained | voice-references | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | 1/1 | - | - | 4/4 | 4/4 |

**Total: A 238/369, B 229/369**

## Criterion pass rates (all models, all trials)

| suite | criterion | A | B |
|---|---|---|---|
| aside-outpost-routing | aside | 12/16 | 11/13 |
| aside-outpost-routing | aside_then_outpost | 2/3 | 2/2 |
| aside-outpost-routing | outpost | 2/10 | 1/10 |
| base-first-reading | assume | 2/4 | 2/4 |
| base-first-reading | direct | 8/8 | 8/8 |
| base-first-reading | reframe | 8/20 | 7/20 |
| base-single-answer | delete-stale | 4/4 | 4/4 |
| base-single-answer | one-place | 0/4 | 0/4 |
| base-single-answer | replace-not-amend | 4/4 | 4/4 |
| base-single-answer | rewrite-not-negate | 4/4 | 4/4 |
| base-test-scope | derive | 2/9 | 2/9 |
| base-test-scope | fix-code | 3/3 | 4/4 |
| base-test-scope | no-prose-pin | 4/4 | 3/3 |
| base-test-scope | pin-requested | 4/4 | 4/4 |
| base-user-terms | full-delivery | 1/4 | 3/4 |
| base-user-terms | no-commentary | 0/7 | 1/7 |
| base-user-terms | rule-verbatim | 5/6 | 4/6 |
| base-user-terms | settled-suggestion | 4/4 | 4/4 |
| base-user-terms | still-corrects | 2/6 | 2/6 |
| judgment-rewrite-new | expect | 93/116 | 89/116 |
| judgment-rewrite-new | korean-casual | 96/113 | 90/113 |
| judgment-rewrite-new | no-fail_if | 67/77 | 70/77 |
| judgment-rewrite-new | no-opening-label | 110/112 | 107/113 |
| lead-rail-choice | evidence-selected | 21/22 | 21/22 |
| lead-rail-choice | expect | 12/22 | 13/22 |
| lead-rail-choice | inline | 4/4 | 4/4 |
| lead-rail-choice | preflight.candidate_read | 8/10 | 7/10 |
| lead-rail-choice | team | 6/10 | 7/10 |
| lead-visual-medium | checked-before-link | 0/4 | 0/4 |
| lead-visual-medium | mermaid-rendered | 9/12 | 8/8 |
| lead-visual-medium | outside-repo | 9/14 | 7/14 |
| lead-visual-medium | shown-inline | 10/16 | 8/12 |
| lead-visual-medium | video-delegated | 4/4 | 4/4 |
| lead-visual-medium | visual-carries-it | 0/4 | 0/4 |
| lead-visual-medium | words-stay-words | 8/8 | 8/8 |
| voice-opening | natural-korean | 5/11 | 3/11 |
| voice-opening | no-opening-label | 21/23 | 21/23 |
| voice-opening | soft-casual | 6/12 | 7/12 |
| voice-references | content-not-pointer | 3/4 | 3/4 |
| voice-references | no-gloss-crutch | 5/6 | 3/6 |
| voice-references | user-words-stay | 4/4 | 4/4 |

## Cells where the pass rate differs (B - A)

| case | model | A | B | delta |
|---|---|---|---|---|
| literal-fix-misses-goal | opus | 3/3 | 0/3 | -1.00 |
| model-generation-swap | astra | 1/1 | 0/1 | -1.00 |
| fix-and-report | astra | 1/1 | 0/1 | -1.00 |
| open-discussion | opus | 3/3 | 0/3 | -1.00 |
| decision-advice | astra | 1/1 | 0/1 | -1.00 |
| design-review-density | opus | 3/3 | 1/3 | -0.67 |
| design-review-density | sol | 3/3 | 1/3 | -0.67 |
| language-after-english-work | sol | 3/3 | 1/3 | -0.67 |
| boxed-diagram | ds | 3/3 | 1/3 | -0.67 |
| no-coined-names | opus | 3/3 | 1/3 | -0.67 |
| citation-vs-claim | ds | 2/3 | 0/3 | -0.67 |
| logged-in-saas | ds | 3/3 | 2/3 | -0.33 |
| korean-ui-copy | ds | 3/3 | 2/3 | -0.33 |
| thinking-out-loud | ds | 3/3 | 2/3 | -0.33 |
| architecture-review | sol | 1/3 | 0/3 | -0.33 |
| model-generation-swap | astram | 1/3 | 0/3 | -0.33 |
| user-number-rule | ds | 2/3 | 1/3 | -0.33 |
| citation-vs-claim | opus | 1/3 | 0/3 | -0.33 |
| design-review-density | ds | 1/3 | 0/3 | -0.33 |
| fix-and-report | ds | 2/3 | 1/3 | -0.33 |
| fix-and-report | astram | 2/3 | 1/3 | -0.33 |
| open-discussion | ds | 2/3 | 1/3 | -0.33 |
| decision-advice | ds | 1/3 | 0/3 | -0.33 |
| work-report | ds | 2/3 | 1/3 | -0.33 |
| crowded-doc-feedback | sol | 1/3 | 2/3 | +0.33 |
| language-after-english-work | ds | 1/3 | 2/3 | +0.33 |
| material-choice-with-recommendation | sol | 0/3 | 1/3 | +0.33 |
| decision-advice | sol | 1/3 | 2/3 | +0.33 |
| collect-only | ds | 2/3 | 3/3 | +0.33 |
| hiring-market-research | opus | 2/3 | 3/3 | +0.33 |
| delegation-brief | ds | 2/3 | 3/3 | +0.33 |
| language-after-english-work | astram | 2/3 | 3/3 | +0.33 |
| downstream-question | ds | 0/3 | 2/3 | +0.67 |
| model-generation-swap | opus | 0/3 | 2/3 | +0.67 |
| collect-only | opus | 1/3 | 3/3 | +0.67 |
| korean-ui-copy | astram | 1/3 | 3/3 | +0.67 |
| work-report | opus | 1/3 | 3/3 | +0.67 |
| full-delivery | opus | 0/1 | 1/1 | +1.00 |
| full-delivery | ds | 0/1 | 1/1 | +1.00 |
| inflate-resume | astra | 0/1 | 1/1 | +1.00 |
| gate-friction | ds | 0/1 | 1/1 | +1.00 |
| flow-planning | sol | 0/3 | 3/3 | +1.00 |
