# Security

## Intended users
Yannick Senah (student)
Professor Lamoureux. and associated TA's for CSE3000

## Risk assessment
If the code/data in this repo fell into the wrong hands, the main risks would be:
- Academic integrity concerns (someone could copy solutions).
- Exposure of any accidentally committed secrets (API keys, tokens, passwords).
- Leakage of private info if any personal data were ever added (should not be).

## Steps taken to secure the repo
- I do not store secrets (API keys/tokens/passwords) in the repository.
- I use a `.gitignore` to avoid committing environment files (e.g., `.env`, build outputs, local configs).
- The repository visibility is set appropriately (private if allowed/needed for the class).
- If collaborating, I would use GitHub protections such as required reviews / rulesets / CODEOWNERS. For this class repo, these controls are not strictly necessary because it is a small student project with limited access.