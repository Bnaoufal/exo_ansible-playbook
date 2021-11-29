# exo_ansible-playbook
Create a small ansible project that writes the contents of a variable (command line environment variable or using ansible’s way of declaring variables) into an output file /tmp/var_output.ansible located on the local machine. The requirements are the following:
•	The main playbook must use a role where the actual write operation is performed
•	When the variable is written in the output file and only if its value changed, the service “myservice.service” should be restarted (be aware of the permissions for such operations)
•	The project must be maintainable and structured, meaning that other roles or other variables could be added in the future.

