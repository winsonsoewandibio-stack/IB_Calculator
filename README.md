# IB Scorecard

A lightweight IB Diploma Programme grade calculator. Enter grades for six subjects and your Extended Essay and Theory of Knowledge to estimate a total score out of 45.

## Run locally

Open `index.html` in a modern web browser. No installation or build step is required.

The calculator offers subject choices from the six IB subject groups, then adds the six subject grades (up to 42 points) to the core bonus (up to 3 points), using the EE/TOK bonus matrix.

The percentile shown is a planning approximation, not an official IB publication. It uses a normal-distribution model centered on the 2024 global Diploma Programme average of 30.32. Subject choices and individual HL/SL subject distributions are not yet modelled, and percentile estimates should not be used for official admissions decisions.

## Publish with GitHub Pages

The GitHub Actions workflow in `.github/workflows/deploy-pages.yml` deploys the site whenever changes are pushed to `main`. After the first successful deployment, the site will be available at:

https://winsonsoewandibio-stack.github.io/IB_Calculator/

In the repository settings, make sure **Pages → Build and deployment → Source** is set to **GitHub Actions** if it is not configured automatically.