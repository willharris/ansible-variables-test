### Sample project showing some problems with Ansible variable handling

Execute:

    ansible-playbook test.yml -i test_inv

Output recorded in output-194.txt and output-2002.txt.

Difference between 1.9.4 and 2.0.0.2:
* in 1.9.4 it is possible to override the "all" variable in the inventory.
* in 2.0.0.2 the inventory variable is ignored.

