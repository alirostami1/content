# Content (Public)

Public subset of the Obsidian vault that powers the published articles, reviews, snippets, and updates in this repo. See `LICENSE` for reuse details.

## Automatic rebuild and deployment

To dispatch to a remote repository you must create a Personal Access Token (PAT) with the repo scope and store it as a secret. If you will be dispatching to a public repository then you can use the more limited public_repo scope.

You can also use a fine-grained personal access token (beta). It needs the following permissions on the target repositories:

contents: read & write
metadata: read only (automatically selected when selecting the contents permission)
