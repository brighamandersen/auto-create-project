1. Make sure that `GH_PAT` is an environment variable. You can generate it if needed at [this area of GitHub](https://github.com/settings/tokens).  
   Add it to your `~/.bashrc` or `~/.zshrc`: `export GH_PAT="{TOKEN}"`

2. Also make sure to add the `git-create` file to your PATH so that you can run in from outside the scope of this repo (you'll want to run it where you save your new repo on your machine - `~/Code` directory for me).

Here's how to do that on Mac:

```
export PATH=$PATH:/Users/...path-to-project
```

Here's specifically what I'm using as of now:

```
export PATH=$PATH:/Users/brig/Code/auto-create-project
```
