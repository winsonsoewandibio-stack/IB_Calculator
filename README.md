# IB Scorecard

A lightweight IB Diploma Programme grade calculator. Enter grades for six subjects and your Extended Essay and Theory of Knowledge to estimate a total score out of 45.

## Run locally

Open `index.html` in a modern web browser. No installation or build step is required.

The subject groups and course categories follow the [official IB DP curriculum](https://www.ibo.org/programmes/diploma-programme/curriculum/). Group 6 can be Arts or an additional subject from Groups 1–4; the selector updates its course list to match. Literature and performance and environmental systems and societies appear under both groups they can satisfy. Specific language offerings vary by school. The calculator adds six subject grades (up to 42 points) to the core bonus (up to 3 points), using the EE/TOK bonus matrix. It also includes an eligibility estimate based on the [official IB DP passing criteria](https://www.ibo.org/about-the-ib/what-it-means-to-be-an-ib-student/recognizing-student-achievement/about-assessment/dp-passing-criteria/): 24 total points, CAS completion, no grade 1, limits on grades 2 and 3 or below, HL and SL point thresholds, and the EE/TOK grade conditions. It does not verify course compatibility or content-overlap restrictions, which should be confirmed with the DP coordinator.

The percentile shown is a planning approximation, not an official IB publication. It uses a normal-distribution model centered on the 2024 global Diploma Programme average of 30.32 and does not model subject choices or HL/SL grade distributions. Percentile estimates should not be used for official admissions decisions.

## Publish with GitHub Pages

The GitHub Actions workflow in `.github/workflows/deploy-pages.yml` deploys the site whenever changes are pushed to `main`. After the first successful deployment, the site will be available at:

https://winsonsoewandibio-stack.github.io/IB_Calculator/

In the repository settings, make sure **Pages → Build and deployment → Source** is set to **GitHub Actions** if it is not configured automatically.