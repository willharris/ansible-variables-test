### Sample project showing some problems with Ansible variable handling

Execute:

    ansible-playbook test.yml -i test_inv

Output recorded in output-194.txt and output-2002.txt.

Behavior mostly as expected, except:
* overridden variable definition in inventory for `test_grp` is ignored.

No difference in behavior between 1.9.4 and 2.0.0.2. 

