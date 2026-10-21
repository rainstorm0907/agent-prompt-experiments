# Skill test: O vs P (opus, sol)

| case | model | content O | content P | read O | read P |
|---|---|---|---|---|---|
| ui-draft-feedback | opus | 2/3 | 2/3 | 2/3 | 1/3 |
| ui-draft-feedback | sol | 1/3 | 2/3 | 3/3 | 3/3 |
| outpost-mismatch | opus | 2/3 | 2/3 | 3/3 | 2/3 |
| outpost-mismatch | sol | 0/3 | 3/3 | 3/3 | 3/3 |
| product-feature-decision | opus | 3/3 | 3/3 | 0/3 | 0/3 |
| product-feature-decision | sol | 3/3 | 3/3 | 3/3 | 3/3 |
| prompt-improve | opus | 2/3 | 2/3 | 0/3 | 0/3 |
| prompt-improve | sol | 0/3 | 0/3 | 0/3 | 3/3 |

| cond | content | opus | sol | target skill read | avg input tok/run | avg output tok/run |
|---|---|---|---|---|---|---|
| O | 13/24 | 9/12 | 4/12 | 14/24 | 327,149 | 5,683 |
| P | 17/24 | 9/12 | 8/12 | 15/24 | 282,614 | 5,510 |
