JSON file for packer that creates a 10GB cloud image containing provisioning tools.

Status:
Ubuntu 16.04
Instance size Small
Docker (latest - 17.09.0-ce)
  - Docker Compose, version 1.17, hard coded. Checksum not checked.
Ansible (latest - 2.3.2.0)
Packer (v. 1.1.1) 
Singularity (v. 2.4)

To use, first source your OpenStack RC File and then run packer build vmtemplate.json
