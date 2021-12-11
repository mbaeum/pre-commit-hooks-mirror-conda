# pre-commit-hooks-mirror-conda
Mirror of black for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit For pre-commit-hooks: see https://github.com/pre-commit/pre-commit-hooks

Using pre-commit-hooks with pre-commit and conda:
Add something like this to your .pre-commit-config.yaml

```yml
 - repo: https://github.com/mbaeum/pre-commit-hooks-mirror-conda
   rev: '4.0.1' # add tag here
   hooks:
    - id: trailing-whitespace
```
For all available hooks check .pre-commit-hooks.yaml
