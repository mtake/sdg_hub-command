# sdg_hub-command
Workspace for [sdg_hub](https://github.com/mtake/sdg_hub)<br/>

## Setup

### Create and enable a new Python environment (>=3.9,<3.13)
Example with pyenv-virtualenv
```bash
pyenv update
pyenv install 3.11.11
pyenv virtualenv 3.11.11 sdg_hub
pyenv local sdg_hub
pip install -U pip
```

### Install sdg_hub
```bash
#git clone git@github.com:Red-Hat-AI-Innovation-Team/sdg_hub.git
git clone git@github.com:mtake/sdg_hub.git
(cd sdg_hub; pip install -e .)
```

### Configure environments for RITS, and DMF
```bash
# for RITS (request API key at https://rits.fmaas.res.ibm.com/)
(cd sdg_hub; echo "RITS_API_KEY=<your_api_key>" >> fms_dgt/.env)
```

### Note for VS Code Users
Navigate through `File` -> `Open Folder...` -> move to `sdg_hub` directory and `Open`.
