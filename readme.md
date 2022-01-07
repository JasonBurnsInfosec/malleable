This code doesn't "do" anything.
This is a malleable shell playbook made to quickly throw in arbitrary code and run without time on playbook setup.

hosts.yml holds inventory list to be run against.

malleable.yml specifies which host types from inventory run which roles.

group_vars contains variables that can be shared among different roles.

run the playbook with "ansible-playbook malleable.yml -i ./hosts"


good luck and try harder.
