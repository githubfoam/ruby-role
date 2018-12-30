ruby-role
=========
circleci branch:
[![](https://img.shields.io/circleci/project/github/githubfoam/ruby-role/circleci.svg?style=plastic)](https://circleci.com/gh/githubfoam/ruby-role)




----------------

Playbook
----------------

molecule testinfra/goss travisci:

    - MOLECULE_SCENARIO=centos74-goss
    - MOLECULE_SCENARIO=centos74-testinfra
    - MOLECULE_SCENARIO=ubuntu1804-goss
    - MOLECULE_SCENARIO=ubuntu1804-testinfra




License
-------

GNU General Public License v3.0

Author Information
------------------

An optional section for the role authors
