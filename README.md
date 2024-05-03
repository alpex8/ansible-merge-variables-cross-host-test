# Set Up

1. `virtualenv .venv`
2. `source .venv/bin/activate`
3. `pip install -r requirements.txt`
4. `source .venv/bin/activate`  # otherwise system wide installed ansible-playbook will be used
5. `ansible-playbook -i hosts.yml play_merge.yml`
