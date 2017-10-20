JSON file for packer that creates a 10GB cloud image that contains other tools.

Status:
Ubuntu 16.04
Instance size Small
Docker (latest?)
Ansible (latest)
Packer (v. 1.1.1) 
Singularity (v. 2.3.1)

To use, first source your OpenStack RC File and then run packer build vmtemplate.json
