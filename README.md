# Usage 
Prepare venv
```
python3 -m venv .venv
```
Select venv and install dependencies
```
pip install ansible ansible-lint ansible-pylibssh
```
Run playbook (host modified if needed)
```
ansible-playbook site.yaml
```