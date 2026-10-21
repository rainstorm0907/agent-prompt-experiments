# Wave 1 results

Overall per cell: P = pass, F = fail (any criterion failed), ? = not judged, · = not run. Criterion detail: `n/o` = not observable in the record.

Models: opus = anthropic/claude-opus-5-5 high, sol = openai-codex/gpt-6.1-sol high, astra = openai-codex/gpt-6-astra xhigh, ds = opengateway/deepseek/deepseek-v4.1-flash-ultrafast high

## base-user-terms

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| inflate-resume | F | F | F | F | F | P | F | F |
| user-number-rule | P | P | P | P | P | P | F | P |
| full-delivery | F | P | F | F | P | P | F | P |
| declined-suggestion-stays-down | P | P | P | P | P | P | P | P |
| partner-not-yes-man | P | P | F | F | F | F | P | F |

## base-first-reading

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| downstream-question | P | P | F | F | F | F | F | P |
| false-premise | P | P | P | P | P | P | P | P |
| goal-only-user-knows | F | F | F | F | F | F | F | F |
| clear-request | P | P | P | P | P | P | P | P |
| clear-bugfix | P | P | P | P | P | P | P | P |
| safe-reversible-choice | P | P | F | F | F | F | P | P |
| literal-fix-misses-goal | P | F | F | F | F | F | F | F |

## base-single-answer

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| wrong-fact-in-readme | P | P | P | P | P | P | P | P |
| rule-already-elsewhere | F | F | F | F | F | F | F | F |
| changed-rule | P | P | P | P | P | P | P | P |
| removed-feature | P | P | P | P | P | P | P | P |

## base-test-scope

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| model-generation-swap | F | P | F | F | P | F | F | F |
| routing-regression | P | P | P | P | P | P | P | P |
| prompt-rewording | P | P | P | P | P | P | P | P |
| stated-default | P | P | P | P | P | P | P | P |

## voice-opening

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| concept-explain | P | P | F | F | F | F | F | F |
| decision-advice | F | F | F | P | P | F | P | F |
| work-report | F | P | P | P | P | P | P | F |

## voice-references

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| summary-after-long-thread | P | P | P | P | P | P | F | F |
| no-coined-names | P | F | P | P | P | P | F | F |
| user-term-not-reexplained | P | P | P | P | P | P | P | P |

## lead-visual-medium

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| simple-concept | P | P | P | P | P | P | P | P |
| options-compared | P | P | P | P | P | P | P | P |
| flow-planning | P | P | F | P | P | P | P | P |
| shape-needs-motion | F | F | F | F | F | F | F | F |
| boxed-diagram | P | P | P | P | P | P | P | F |
| video-requested | P | P | P | P | P | P | F | F |

## aside-outpost-routing

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| current-job-openings | P | P | P | P | P | P | P | P |
| logged-in-saas | P | P | F | F | P | P | P | F |
| interpret-hiring-signals | F | F | F | F | F | F | F | F |
| architecture-review | F | F | P | F | P | P | F | F |
| collect-only | F | P | P | P | P | P | F | P |
| hiring-market-research | F | P | P | P | P | P | P | P |

## lead-rail-choice

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| layers-fe-be-tests | P | P | P | P | P | P | F | P |
| unknown-root-cause | P | P | P | P | P | P | P | P |
| two-parallel-workstreams | F | F | P | P | P | P | F | F |
| explorer-map | P | P | P | P | P | P | P | P |
| single-review | P | P | P | P | P | P | P | P |
| noisy-investigation | P | P | P | P | P | P | P | P |
| couple-of-reads | P | P | P | P | P | P | P | P |
| gate-friction | P | P | P | P | P | P | F | P |
| repository-fact-first | F | F | F | F | F | F | F | F |
| unavailable-source | P | P | P | P | P | P | P | P |
| material-choice-with-recommendation | F | F | F | P | F | F | F | F |
| stop-research-when-ready | P | P | P | P | P | P | P | P |
| small-work-stays-small | P | P | P | P | P | P | P | P |

## judgment-rewrite-new

| case | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B |
|---|---|---|---|---|---|---|---|---|
| crowded-doc-feedback | F | F | F | P | P | P | F | F |
| citation-vs-claim | F | F | F | F | F | F | P | F |
| design-review-density | P | F | P | P | F | F | F | F |
| fix-and-report | P | P | P | P | P | F | P | P |
| thinking-out-loud | P | P | P | P | P | P | P | F |
| korean-ui-copy | P | P | P | P | P | P | P | F |
| delegation-brief | P | P | F | F | F | F | F | P |
| open-discussion | P | F | P | P | P | P | F | F |

## Aggregates: overall pass count per suite

| suite | opus A | opus B | sol A | sol B | astra A | astra B | ds A | ds B | all A | all B |
|---|---|---|---|---|---|---|---|---|---|---|
| base-user-terms | 3/5 | 4/5 | 2/5 | 2/5 | 3/5 | 4/5 | 2/5 | 3/5 | 10/20 | 13/20 |
| base-first-reading | 6/7 | 5/7 | 3/7 | 3/7 | 3/7 | 3/7 | 4/7 | 5/7 | 16/28 | 16/28 |
| base-single-answer | 3/4 | 3/4 | 3/4 | 3/4 | 3/4 | 3/4 | 3/4 | 3/4 | 12/16 | 12/16 |
| base-test-scope | 3/4 | 4/4 | 3/4 | 3/4 | 4/4 | 3/4 | 3/4 | 3/4 | 13/16 | 13/16 |
| voice-opening | 1/3 | 2/3 | 1/3 | 2/3 | 2/3 | 1/3 | 2/3 | 0/3 | 6/12 | 5/12 |
| voice-references | 3/3 | 2/3 | 3/3 | 3/3 | 3/3 | 3/3 | 1/3 | 1/3 | 10/12 | 9/12 |
| lead-visual-medium | 5/6 | 5/6 | 4/6 | 5/6 | 5/6 | 5/6 | 4/6 | 3/6 | 18/24 | 18/24 |
| aside-outpost-routing | 2/6 | 4/6 | 4/6 | 3/6 | 5/6 | 5/6 | 3/6 | 3/6 | 14/24 | 15/24 |
| lead-rail-choice | 10/13 | 10/13 | 11/13 | 12/13 | 11/13 | 11/13 | 8/13 | 10/13 | 40/52 | 43/52 |
| judgment-rewrite-new | 6/8 | 4/8 | 5/8 | 6/8 | 5/8 | 4/8 | 4/8 | 2/8 | 20/32 | 16/32 |
| **all** | 42/59 | 43/59 | 39/59 | 42/59 | 44/59 | 42/59 | 34/59 | 33/59 | 159/236 | 160/236 |

## Aggregates: criterion pass count (all models; not-observable excluded)

| suite | criterion | A | B |
|---|---|---|---|
| ? | expect | 4/4 | 3/4 |
| ? | korean-casual | 3/4 | 3/4 |
| ? | no-fail_if | 4/4 | 4/4 |
| ? | no-opening-label | 4/4 | 4/4 |
| aside-outpost-routing | aside | 7/10 | 7/9 |
| aside-outpost-routing | aside_then_outpost | 2/3 | 2/2 |
| aside-outpost-routing | outpost | 2/8 | 1/8 |
| base-first-reading | assume | 2/4 | 2/4 |
| base-first-reading | direct | 8/8 | 8/8 |
| base-first-reading | reframe | 6/16 | 6/16 |
| base-single-answer | delete-stale | 4/4 | 4/4 |
| base-single-answer | one-place | 0/4 | 0/4 |
| base-single-answer | replace-not-amend | 4/4 | 4/4 |
| base-single-answer | rewrite-not-negate | 4/4 | 4/4 |
| base-test-scope | derive | 1/5 | 1/5 |
| base-test-scope | fix-code | 3/3 | 4/4 |
| base-test-scope | no-prose-pin | 4/4 | 3/3 |
| base-test-scope | pin-requested | 4/4 | 4/4 |
| base-user-terms | full-delivery | 1/4 | 3/4 |
| base-user-terms | no-commentary | 0/5 | 1/5 |
| base-user-terms | rule-verbatim | 3/4 | 4/4 |
| base-user-terms | settled-suggestion | 4/4 | 4/4 |
| base-user-terms | still-corrects | 2/4 | 1/4 |
| judgment-rewrite-new | expect | 32/40 | 28/40 |
| judgment-rewrite-new | korean-casual | 33/39 | 33/39 |
| judgment-rewrite-new | no-fail_if | 21/25 | 22/25 |
| judgment-rewrite-new | no-opening-label | 38/39 | 37/39 |
| lead-rail-choice | evidence-selected | 19/20 | 20/20 |
| lead-rail-choice | expect | 12/20 | 13/20 |
| lead-rail-choice | inline | 4/4 | 4/4 |
| lead-rail-choice | preflight.candidate_read | 6/8 | 6/8 |
| lead-rail-choice | team | 5/8 | 6/8 |
| lead-visual-medium | checked-before-link | 0/4 | 0/4 |
| lead-visual-medium | mermaid-rendered | 7/8 | 6/6 |
| lead-visual-medium | outside-repo | 7/12 | 6/12 |
| lead-visual-medium | shown-inline | 8/12 | 6/10 |
| lead-visual-medium | video-delegated | 4/4 | 4/4 |
| lead-visual-medium | visual-carries-it | 0/4 | 0/4 |
| lead-visual-medium | words-stay-words | 8/8 | 8/8 |
| voice-opening | natural-korean | 2/5 | 1/5 |
| voice-opening | no-opening-label | 13/13 | 13/13 |
| voice-opening | soft-casual | 4/8 | 4/8 |
| voice-references | content-not-pointer | 3/4 | 3/4 |
| voice-references | no-gloss-crutch | 3/4 | 2/4 |
| voice-references | user-words-stay | 4/4 | 4/4 |

