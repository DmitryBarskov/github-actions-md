# GitHub Actions Explained
GitHub Actions is a CI/CD service available for GitHub repositories.

## Therminology
One GitHub repository can have multiple _workflows_. Think of a workflow as
of a trigger or listener for some _event_. Event is some action that takes
place in your repository, e. g. push to main branch, creation of a PR or
an issue.

Each workflow specifies events it should be triggered on and a set of _jobs_
that will run in the same environment. Every job will run inside _runner_ -
its own virtual machine.

![components of github workflow][1]

## Plans
- Free for open source repositories
- Free 2000 minutes/month for private repositories
- Different paid plans already have 3000+ minutes/month
- Every extra minute costs $0.008 (on Linux)

[1]: https://docs.github.com/assets/cb-25535/images/help/images/overview-actions-simple.png
