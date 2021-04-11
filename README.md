# Intro

This template is a quickstarter for ansible sites.

# Sourcing

only nessessary files:

* ansible.cfg
* inventory
	* only the most crucial ini style inventory for you to start with
	* group localhost with member localhost
* site.yml
	* only one sample task "packages"
	* only one sample role "docker_arm" (TODO: subject to change)
* roles/README.md
* roles/.gitignore
* this README.md

License: MIT

Author: github account @callmeconnor

Inspired by: https://github.com/itwars/k3s-ansible
