# queue

An interactive explainer for the statistics of waiting in line, published with GitHub Pages:
**https://nihilisticiconoclast.github.io/queue/**

- **Counting arrivals** — a door with a constant arrival rate; counts per window settle onto
  the Poisson distribution, derived from the binomial.
- **The gap to the next one** — the exponential distribution, its lack of memory shown on the
  same stream, and the bus-stop paradox measured from the gaps.
- **Waiting for the nth customer** — the Erlang distribution and its identity with a Poisson
  tail, as two charts whose shaded areas are always equal.
- **Merging, splitting and racing** — thinning one stream into two, and the race between two
  exponential clocks.
- **One server, and the line behind** — a live M/M/c counter with the simulated long-run
  averages set against the formulas.
- **More tills** — Erlang C run backwards: how many servers for a given service level, and
  why one pooled line beats separate ones.
- **The knee, and what variability costs** — the Pollaczek–Khinchine formula, with a
  200,000-customer simulation at the chosen load and spread.
- **A ready reckoner** — the standard questions, answered for any rates you enter.

Everything is in `index.html`. The house style (palette, type, logo, per-page doodle) is linked
from [cuddly-lamp](https://github.com/nihilisticiconoclast/cuddly-lamp) via jsDelivr, and the
maths is typeset with KaTeX from cdnjs. The page still works if either fails to load.
