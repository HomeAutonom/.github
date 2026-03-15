# Copilot Instructions — .github

## Project

- **Name**: .github
- **Organization**: HomeAutonom
- **Enterprise**: iAiFy
- **Language**: Unknown
- **Description**: Organization profile and shared community health files for HomeAutonom

## Profile Repository

This is the organization profile repository for HomeAutonom.
It contains profile/README.md displayed on the org page,
plus shared governance files (CODEOWNERS, dependabot.yml, agents).

## Conventions

- Use kebab-case for file and directory names
- Use conventional commits (feat:, fix:, chore:, docs:, refactor:, test:)
- All PRs require review before merge
- Branch from main, merge back to main
- All file names in kebab-case

## Shared Infrastructure

- Reusable workflows: Ai-road-4-You/enterprise-ci-cd@v1
- Composite actions: Ai-road-4-You/github-actions@v1
- Governance standards: Ai-road-4-You/governance

## Quality Standards

- Run lint and tests before submitting PRs
- Keep dependencies updated via Dependabot
- No hardcoded secrets — use GitHub Secrets or environment variables
- Follow OWASP Top 10 security practices
