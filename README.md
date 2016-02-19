### Sample project showing some problems with Ansible variable handling

Execute:

    ansible-playbook test.yml -i test_inv

Output recorded in output-194.txt and output-2002.txt.

Change to the inventory:
* the variable is overridden in the inventory on the child group rather than the parent group.

Same behaviour as before, except there is a difference between 1.9.4 and 2.0.0.2:
* in 1.9.4 the overridden child group variable is taken.
* in 2.0.0.2 the variable is ignored, and treated the same as the test_group variable.

