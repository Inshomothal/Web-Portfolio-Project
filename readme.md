# Web3 / Full-Stack Portfolio Hub

This repository tracks the long-term Web3/full-stack roadmap described in [web3-portfolio-plan.md](web3-portfolio-plan.md). The plan outlines the projects, skills, and timeline I’m following from 2025 through 2028 to become job-ready for hybrid Web2/Web3 roles.

## What Lives Here

- **Strategy docs:** The `web3-portfolio-plan.md` file captures the full learning and build plan, while the `docs/` folder contains the Jekyll site that will eventually publish selected notes from the plan.
- **Project directories:** As each portfolio project spins up, its code or submodule link will live inside this repo (or link out to a dedicated repo) so everything stays discoverable from one place.
- **Deployment steps:** Instructions and checklists land in `steps-to-deploy.md` (and any other vault notes I add) so I can repeat deployments quickly.

## How I’ll Use It

1. Start from the written plan, pick the next project/skill focus, and create a corresponding folder or linked repo here.
2. Keep READMEs, diagrams, and deployment notes alongside the code so each project is portfolio-ready.
3. Update the plan and docs as projects finish, then surface highlights on the public site.

## Workflow

- The website is locally tested using `cd "{root folder}/docs"; bundle exec jekyll serve ` after getting the files using `bundle install`.
- The website can be checked with a production build by running `bundle exec jekyll build --source . --destination _site` from the `docs` directory. Make sure you serve with the came command (replace `build` with `serve`) to see how your page will look when deployed.

This repo is the single source of truth for the roadmap and for all code or references to the projects that implement it.
