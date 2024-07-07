
- This project integrates frontend and backend component as submodules (frontend-repo and backend-repo) into a unified fullstack-repo.
- Changes made in submodules reflect automatically in the main repo.
- To get started,clone this repo and set it up locally:
  git clone https://github.com/zaynabmama/fullstack-repo.git
  cd fullstack-repo
  git submodule update --init --recursive
- to work with yaml configuration files (config.yaml)in Python follow these steps:
  Python needs pyyaml installed to work with YAML files .if you haven't installed it yet ,use the following command:pip install pyyaml
  Customize config.yaml with your project's specific settings.
  Ensure submodules (frontend-repo and backend-repo) are updated and synchronized to reflect changes in fullstack-repo.
- Add frontend-repo and backend-repo as submodules to fullstack-repo by using the terminal:
  git submodule add https://github.com/zaynabmama/frontend-repo.git frontend-repo
  git submodule add https://github.com/zaynabmama/backend-repo.git backend-repo

- Modifying config.yaml in fullstack-repo  update the config variables.
 Changes in frontend-repo and backend-repo are automaticaly reflected in fullstack-repo


  
