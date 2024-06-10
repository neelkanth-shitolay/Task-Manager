# cse110-sp24-group16

## Team 16 (Quantuum Leap)

GitHub repo link: [https://github.com/cse110-sp24-group16/cse110-sp24-group16/](https://github.com/cse110-sp24-group16/cse110-sp24-group16/)

[Team Info](./admin/team.md)

[DEVLOG (all changes and progress made, chronologically)](https://github.com/cse110-sp24-group16/cse110-sp24-group16/wiki)

[Documentation (autogenerated)](https://cse110-sp24-group16.github.io/cse110-sp24-group16/out/index.html)

[HTML version of readme and all links](https://cse110-sp24-group16.github.io/cse110-sp24-group16/)

How to run:

`npm start` launches the electron app

CI/CD Pipeline:

- Linter: ESLint, Codacy
  - Check code for proper linting with `npm run lint` in project root.
- External code quality analysis: Codacy
  - Provides information about bad, harmful, or insecure code. Dashboard link: [CODACY](https://app.codacy.com/gh/cse110-sp24-group16/cse110-sp24-group16/dashboard)
- Human review: Protected `main` and `dev` branches
  - First, you have to PR to `dev` branch and it requires code review from 1 person. Please assign several people when creating a PR.
  - Then, after PR to `dev` has been approved and merged, changes will be validated on `dev` and PR'ed into `main` after review from at least 2 people.
- Unit testing: Jest
  - Automatically done on push and PR via automations.
  - Can test code locally using `npm run test` in project root.
- Documentation & autogeneration: JSDoc
  - Document all your code according to JSDoc format.
  - Automatically converts comments into documentation on push/PR.
  - Can locally update documentation with `npm run jsdoc` in project root.
  - Documentation output is in `out/` directory.
- e2e testing: WebDriverIO
  - On PR into `main`, at least 1 person will manually check all functionality of the app.
- Manual Testing:
  - [Manual Testing Report](./source/__tests__/060824-Manual-Testing-Report.md)

Project status and work:

- Tasks: GH Projects and Issues
  - All active and planned tasks can be found in this repository issues and project section with assigned people, tasks description, and completion status.
- Daily standups: Standuply
  - App integration with Slack to conduct standup polls on daily basis, results are posted in a public channel so that everyone can evaluate the work done.
- Tags: Automations
  - If interested in only specific updates (e.g., frontend or CSS), use tags in your search. They are both automatically and manually assigned to every Issue and PR.

### Automatic code evaluation scores

[![Codacy Coverage Badge](https://app.codacy.com/project/badge/Coverage/a35b12c515d74f70811350a600bf47b3)](https://app.codacy.com/gh/cse110-sp24-group16/cse110-sp24-group16/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_coverage)

[![Codacy Quality Badge](https://app.codacy.com/project/badge/Grade/a35b12c515d74f70811350a600bf47b3)](https://app.codacy.com/gh/cse110-sp24-group16/cse110-sp24-group16/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
