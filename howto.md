
mkdir 20231027-create-gh-repos
cd 20231027-create-gh-repos
git init

manually copying .gitignore from: https://github.com/github/gitignore  Python for example

gh repo create 20231027-create-gh-repos --source=. --public --push

gh auth refresh -h github.com -s delete_repo