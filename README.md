# Setup

1. Make a PAT (Personal Access Token). You can generate it if needed at [this area of GitHub](https://github.com/settings/tokens).
2. Make sure that `GH_PAT` is an environment variable.  
   Add it to your `~/.bashrc` or `~/.zshrc`:  
   `export GH_PAT="{TOKEN}"`
3. Add an alias to your `git-create` file so you can run it outside of this git repo. the scopelso make sure to add the `git-create` file to your PATH so that you can run in from outside the scope of this repo:  
   `alias git-create="~/code/auto-create-project/git-create.sh` (Adjust path as needed)

# Usage

Just cd into the directory where you'd like to clone the repo you're about to make and run `git_create`.
