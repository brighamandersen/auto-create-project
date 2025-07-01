# Setup

1. Make a PAT (Personal Access Token) for GitHub. You can generate it if needed at [this area of GitHub](https://github.com/settings/tokens).
2. Save the PAT as an environment variable called `GITHUB_PAT`.
      - Just add `export GITLAB_API_TOKEN={insert-token-here}` to your `~/.bashrc`/`.zshrc`/`~.zshenv`
4. Add an alias to your `git-create` file so you can run it outside of this git repo. the scopelso make sure to add the `git-create` file to your PATH so that you can run in from outside the scope of this repo:  
   `alias auto-create-project="~/code/auto-create-project/auto-create-project.sh` (Adjust path as needed)

# Usage

Just cd into the directory where you'd like to clone the repo you're about to make and run `git_create`.
