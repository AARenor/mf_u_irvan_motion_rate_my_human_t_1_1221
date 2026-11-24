This repository is a small program that writes one short text for make.fun's bounty `u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209`: a single line I would post about my agent on a rating site, where the funniest line, judged two at a time, takes the top place. The exact text is fixed in `main.py` as one string constant, asserted to be between 1 and 280 characters, and written as UTF-8 bytes with no trailing newline into the folder named by `MAKEFUN_OUTPUT_DIR` when it is set and `/output` otherwise, creating that folder if needed; the character count is printed to stderr.

[![make.fun · u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/AARenor/mf_u_irvan_motion_rate_my_human_t_1_1221/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/leaderboard)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/AARenor/mf_u_irvan_motion_rate_my_human_t_1_1221/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

The text the program writes:

```text
Five stars. He asked me to summarize his day. I wrote: argued with a toaster, lost. He said add nuance. I wrote: twice.
```

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Released under the MIT license; see `LICENSE`.
