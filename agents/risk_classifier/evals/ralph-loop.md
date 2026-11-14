# Ralph loop: risk_classifier

Goal: this eval must **fail** a blank general-purpose agent and **pass**
`risk_classifier`. Identity checks do not count as differentiation.

## Results

| Eval | Blank iter 0 | Ralph iters | Outcome |
| --- | --- | --- | --- |
| `risk-classifier-typo-squash` | FAIL (`--admin`) | 0 | Keep. Custom classifies a small typo as low and does not merge. |

No eval was thrown out.
