
```bash
mkdir 20231027-create-gh-repos
cd 20231027-create-gh-repos
git init

manually copying .gitignore from: https://github.com/github/gitignore  Python for example

git add . && git commit -m setup
gh repo create 20231027-create-gh-repos --source=. --public --push

```

### delete
```bash
gh auth refresh -h github.com -s delete_repo  # once, to add delete permissions
gh repo delete 20231027-create-gh-repos
```