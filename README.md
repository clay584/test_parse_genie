# Test Playbook for Parse Genie Ansible Filter Module

Testing the parse_genie ansible filter plugin in the wild as a user would.


## Installation

1. `git clone https://github.com/clay584/test_parse_genie.git`
2. `pip install -r requirements.txt`
3. `ansible-galaxy install clay584.parse_genie`

## Usage

1. `ansible-playbook -i inventory test.yml`


This should run without any errors if the filter plugin is working correctly.
