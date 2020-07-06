# Keeping Beautiful Repos

> Questions, comments or ideas on how we can make this document better? Your contributions to this doc are very much appreciated.


## The README
- This is your first point of interaction with other people trying to use your code - spending time to craft this file and keep it updated is a mark of a true professional.
- Include sections on:
    - Installation
    - Usage examples
    - Documentation
    - Development setup & contributing
- Writing a friendly Readme. Here’s GitHub’s take as well.
- Too long? Maybe add a table of contents.
- Use badges.
- Check out a curated list of awesome READMEs.
- More advice and a basic starter template over at https://www.makeareadme.com/.
- A more advanced template here: https://gist.github.com/PurpleBooth/109311bb0361f32d87a2.


## The License
- https://opensource.guide/legal/ provides a great overview on what you need to know.
- Use https://choosealicense.com/ and https://tldrlegal.com/ to figure out the best license type.


## Contributing Guidelines
- There’s a good template here.
- Include sections on:
    - Instructions on how to work in the codebase locally
    - Testing instructions
    - Submitting issues and PRs
- Check out the Contributor Covenant code of conduct.


## Repo Artifacts
- Always include a proper `.gitignore` file - here’s a collection of templates.
- Enforce code quality and code style by committing linter tool configurations. Include code style guidelines in the documentation.
- Use hooks to trigger linters and code formatters.
- Hook in analysis tools:
    - Free for OSS: https://codeclimate.com/oss/ 
    - Free to run yourself: https://github.com/codeclimate/codeclimate and https://hub.docker.com/r/codeclimate/codeclimate/
- Setup a CI pipeline, commit test & build configuration to repo.
    - https://circleci.com/ and https://travis-ci.org/ are great free options.
    - GitLab has a great CI. GitHub has actions.
- Include Editor/IDE configuration files.
- Never commit secrets!
    - Hook in https://github.com/awslabs/git-secrets
    - Use dotenv files.
- Leverage the CODEOWNERS file.
- Setup issue and PR templates (or here, if you’re on GitLab). Get inspiration from:
    - https://github.com/stevemao/github-issue-templates
    - https://github.com/devspace/awesome-github-templates


## Commit & Review Guidelines
- Use Conventional Commits.
- Be consistent.
- Some great guides on writing PRs:
    - https://www.braintreepayments.com/blog/effective-pull-requests-a-guide/
    - https://holgerfrohloff.de/best-practices-on-doing-pull-requests/
- Check out Code Review guidelines from Google. Here’s StackOverflow’s take.
- GitHub has a guide on mastering issues.
- Use automation to improve your workflow on GitHub: https://github.com/probot/probot


## Great Resources
- https://open.nytimes.com/how-to-take-your-open-source-project-from-good-to-great-49c392175e5c
- Many excellent guides around OSS here: https://opensource.guide/
- A set of OSS best practices: https://10up.github.io/Open-Source-Best-Practices/
- https://guides.github.com/ is a comprehensive list of guides for everything GitHub related.
