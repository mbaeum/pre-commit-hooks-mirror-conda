# pre-commit-hooks-mirror-conda
Mirror of black for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit For pre-commit-hooks: see https://github.com/pre-commit/pre-commit-hooks

Using pre-commit-hooks with pre-commit and conda:
Add something like this to your .pre-commit-config.yaml

```yml
- repo: https://github.com/pre-commit/pre-commit-hooks
  rev: v4.0.1  # Use the ref you want to point at
  hooks:
  -   id: trailing-whitespace
```