# BasisLens uptime

A GitHub Actions check that loads basislens.com, its API health endpoint and the sign-in page every 10 minutes from
GitHub's servers. Each address gets two tries 45 seconds apart. If one still fails, the run fails and GitHub emails the
repository owner.

- Run it now: Actions → Uptime → Run workflow.
- A monthly keep-alive commit stops GitHub from pausing the schedule after 60 days without activity.
- This repository holds no code, keys or private data: only the three public addresses.
