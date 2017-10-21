## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) debops_fact

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-debops_fact.svg?style=flat)](https://travis-ci.org/debops/ansible-debops_fact)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--debops__fact-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-debops_fact/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.debops_fact-660198.svg?style=flat)](https://galaxy.ansible.com/debops/debops_fact)


The `debops.debops_fact` Ansible role can be used to read JSON data from
a set of INI configuration files and make them available as Ansible local
facts. This mechanism can be used to maintain common facts between separate
Ansible roles without the need for them to know about the specific file
structures, using `ini_file` Ansible module.

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.debops_fact
```

### Documentation

More information about `debops.debops_fact` can be found in the
[official debops.debops_fact documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-debops_fact/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](https://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).