# Contributing to Cloud Guardrails
We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting an issue
- Discussing guardrails
- Submitting a fix
- Proposing new guardrails
- Becoming a maintainer

## We Develop with Github
We use github to host code, to track issues and feature requests, as well as accept pull requests.

## We Use Github, So All Code Changes Happen Through Pull Requests
Pull requests are the best way to propose changes to the codebase. We actively welcome your pull requests:

1. Fork the repo and create your branch from `main`.
2. If you are adding a new guardrail, write them in YAML and keep the names short but descriptive
3. If you are proposing changes to a guardrail, please leave details about what you're changing and why
4. Issue a pull request!

## Any contributions you make will be under the MIT Software License
In short, when you submit code changes, your submissions are understood to be under the same [MIT License](http://choosealicense.com/licenses/mit/) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report bugs using Github's [issues](https://github.com/Resourcely-Inc/cloud-guardrails/issues)
We use GitHub issues to track public bugs. Report a bug by [opening a new issue](); it's that easy!

## Guardrails should use our standard format

**Guardrails** have (in order):

- UUID: a UUID to identify the guardrail
- Authors
- A name (keep these short – 3-5 words)
- Categories (please use an existing category if applicable)
  - Current categories are: `Architecture`, `Change Management`, `Configuration`, and `Process`
  - A guardrail can have more than one category
- Functions (please use an existing function if applicable)
  - Current functions are: `Compliance`, `Cost Management`, `Reliability`, `Security`, and `Standards`
  - A guardrail can have more than one function
- Resources: applicable resources the guardrail applies to
- Maturity: what maturity level an organization should be before attempting to meet the guardrail
- CSPs: AWS, Azure, GCP
- Applies: text description of when the guardrail does/doesn't apply
- Summary: short-form text summary of the guardrail
- How_to: long-form text or code snippet for describing how to implement the guardrail
- Description: long-form text for the user to understand the guardrail
- Links: a list of applicable links

## Valid YAML
Please ensure that all guardrails (and changes) are valid YAML with the correct fields.

## License
By contributing, you agree that your contributions will be licensed under its MIT License.

## References
This document was adapted from this [template](https://gist.github.com/briandk/3d2e8b3ec8daf5a27a62).