# openshiftinventories

important links:
http://www.projectatomic.io/docs/quickstart/

https://github.com/projectatomic/atomic-host-tests/issues/209
## clone openshift-ansble repo run following commands
# commands 
ansible-playbook -vvv -i minv36 openshift-ansible/playbooks/byo/config.yml -e"openshift_disable_check=disk_availability,docker_storage,memory_availability" -e ansible_python_interpreter=/usr/bin/python3 --private-key ~/.ssh/id_rsa
