## Create a new virtual environment
`pip -m venv .venv`
## Install dependencies
`pip install -r requirements.txt`

## Add a dependnecy
1. add the dependency to requirements.in
2. run `pip-compile` to generate the new requirements.txt
3. install `pip install -r requirements.txt`
