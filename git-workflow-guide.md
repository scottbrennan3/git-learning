
# Practical Git Command Cheatsheet

## Start a Repository

```bash
git init
git status
```

## Stage and Commit Changes

```bash
git add README.md
git commit -m "docs: update README"
```

## Inspect History

```bash
git log --oneline
git diff
```

## Work with Branches

```bash
git switch -c feature/add-search
git switch main
```

## Update from Remote

```bash
git pull
git push -u origin feature/add-search
```

## Helpful Habits

- Check git status before committing.
- Write meaningful commit messages.
- Review staged changes.
- Never commit passwords or API keys.
