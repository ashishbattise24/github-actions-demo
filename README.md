# GitHub Actions Demo

Simple Python project demonstrating GitHub Actions CI/CD.

## Pipeline

The workflow contains three jobs:

1. Test
2. Build
3. Deploy

Pipeline flow:

Test -> Build -> Deploy

## Triggers

The workflow runs when:

- Code is pushed to main
- Code is pushed to develop
- A pull request is created against main
- The workflow is manually triggered

## Manual Execution

Go to:

GitHub Repository -> Actions -> Python CI Pipeline -> Run workflow
