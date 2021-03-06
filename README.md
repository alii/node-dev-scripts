# node-dev-scripts

Helper scripts for workspace management.

## GitHub

### bulk-transfer-repos.js

- Create .env in root folder (`node-dev-scripts/.env`) with the following variables:
  - ACCESS_TOKEN
    - Github personal access token.
  - OLD_ORG
    - The organization name you want to transfer repos away from.
  - NEW_ORG
    - The organization name you want to transfer repos to.
- Run `npm install` to install dependencies.
- Start with `node .` or `node index.js`.

### change-remote-urls.js

- Create .env in root folder (`node-dev-scripts/.env`) with the following variables:
  - ACCESS_TOKEN
    - Github personal access token.
  - DIRECTORY
    - Where all the repository folders are located.
  - ORG_NAME
    - GitHub organization name for creating .git URL that origin will be changed to.
  - SSH (Optional)
    - Set to TRUE if you would like your links to use SSH.
- Run `npm install` to install dependencies.
- Start with `node change-remote-urls.js`

### bulk-clone-repos.js

- Create .env in root folder (`node-dev-scripts/.env`) with the following variables:
  - ACCESS_TOKEN
    - Github personal access token.
  - ORG_DIR
    - Where you would like all organization repos to be cloned in to.
  - ORG_NAME
    - GitHub organization name for fetching available repos.
  - SSH (Optional)
    - Set to TRUE if you would like your links to use SSH.
- Run `npm install` to install dependencies.
- Start with `node change-remote-urls.js`

## VSCode

### create-vscode-workspace.js

- Create .env in root folder (`node-dev-scripts/.env`) with the following variables:
  - WORKSPACE_PATH
    - Absolute path where your workspace folders are + where the .code-workspace file will be saved.
  - WORKSPACE_NAME
    - What you would like to name the .code-workspace file.
- Run `npm install` to install dependencies.
- Start with `node change-remote-urls.js`
