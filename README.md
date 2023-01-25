# DISCONTINUATION OF PROJECT #
This project will no longer be maintained by Intel.
Intel has ceased development and contributions including, but not limited to, maintenance, bug fixes, new releases, or updates, to this project.
Intel no longer accepts patches to this project.
# virtual_machine_image_recipes
Packer build templates to create Virtual Machine Images for various cloud service providers with the Intel® Distribution for Python* built-in.

- Utilizes [Hashicorp's Packer](https://www.packer.io) to automate the building of Virtual Machine Images with Intel's accelerated Python distribution.  
- Templates for for both Python 2 and 3 variants, in addition to _core_ and _full_ package combos.  

As easy as making the following call to build the VMI:
```
packer build idp_ami_ubuntu3_full.json 
```
Once completed, packer will shut down the instance used to build this VMI, and return to you the VMI id as a build artifact.
