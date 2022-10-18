# eos

Run Execute playbook without setting maximum pod
ansible-playbook -v -i hosts main.yaml

With maximum pod
ansible-playbook -v -i hosts -e max=3 main.yaml
