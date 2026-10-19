# shimon sorkin

product engineer in tel aviv: about a year and a half of engineering, on top of growth work since 2021.

my repositories are private: promethee's and the moscow times' code is theirs, and shimi is pre-launch. i'm glad to walk through shimi's code on a call.

**what i've shipped**

- **promethee**, paris, jul to oct 2026. first engineer after the co-founder on a mac and windows app that turns focused work into a multiplayer game: 494 commits and 92 merged PRs before the october 2026 launch.
  - took over the windows version and owned it through launch: traced freezes to failed window repainting, added self-recovery and a safe graphics mode for startup driver crashes.
  - fixed crash reporting that a miswired sink was silently dropping, scrubbed user home paths from it, and stopped one machine's crash loop overwhelming fleet reporting.
  - built chat features: edits, replies, reactions, blocking, a hardened send queue and photos encrypted on the device.
- **the moscow times**, since 2023.
  - took crowdfunding from $5k a month to a peak month of €34k (december 2025); recurring donors went from 400 to 2,200 (5.5x).
  - built the donor platform readers give through, since 2025 (next.js, typescript, supabase/postgres): checkout, failed-payment recovery, a donor account in three languages, 19 dashboards. live at [themoscowtimes.com/contribute](https://www.themoscowtimes.com/contribute).
- **shimi**, since september 2026, pre-launch. a local-first windows focus app: a gemini judge checks the window in front against your goals, under a $20 monthly spend cap enforced in code. checked against a stronger model's labels on a week of real use, it caught 47 of 49 off-task windows, with 3 false alarms on 52 on-task ones. its chat runs on the user's own claude or chatgpt login and uses the app's tools over MCP.

**stack:** typescript, react, electron, next.js, postgres and supabase, sqlite, python. LLMs: gemini, the claude agent SDK, MCP, evals.

**working together:** remote, as a contractor, full-time or part-time, from tel aviv (UTC+2/+3).
shimonsorkin@gmail.com · [linkedin](https://linkedin.com/in/shimonsorkin)
