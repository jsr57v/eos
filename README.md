# eos


## Ready to run on minikube


Run Execute playbook without setting maximum pod

ansible-playbook -v -i hosts main.yaml

With maximum pod

ansible-playbook -v -i hosts -e max=3 main.yaml

A list of all pods will be created in list_pod.out on localhost.

