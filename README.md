# github-action-pr-checklist

This repository contains an example process for increasing code quality during pull request review.

The file `.github/PULL_REQUEST_TEMPLATE.md` is an example template that can be modified to include a variety of manual checks in the PR description.

Once submitted, the action defined in `.github/workflows/pr-checklist-dblcheck.yml` will fire each time the PR description is edited. If all tasks are complete the check will pass, otherwise it will fail.
