# Contributing

Thanks for contributing to Quanvolutional.

## Workflow

1. Create a branch from `main` with a descriptive name.
2. Make focused changes (small, reviewable commits).
3. Run quality checks locally before opening a PR.
4. Document any experiment-impacting changes in `README.md` or notebook markdown.

## Coding Standards

- Prefer clear, descriptive variable/function names.
- Keep functions small and composable.
- Add docstrings for reusable utilities.
- Avoid hidden state in notebooks; make execution order explicit.

## Notebook Standards

- Keep long exploratory output to a minimum before committing.
- Add markdown context before major experiment sections.
- Keep imports near the top and avoid duplicate import blocks.

## Local Checks

Run the following before submitting:

```bash
python -m compileall .
ruff check .
black --check .
```

If checks fail, fix issues and rerun.
