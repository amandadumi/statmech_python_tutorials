
# Generate new content

- `hugo create path` e.g. `hugo creat content/session02/index.md`
- edit file

# Generate Hugo site locally
- `hugo` <- generates the static site to the folder `public`
- `hugo serve` <- view it locally

# Push to `gh_pages` branch
- Move the `public` folder somewhere outside of the git folder
- `git checkout gh_pages`
- `rm -rf *`
- `git checkout .gitignore LICENSE.md`
- `cp -r PATH_TO_PUBLIC_FOLDER/public/* .`
- add+commit+push

