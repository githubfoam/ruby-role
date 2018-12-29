ruby
=========


Travis (.com) branch:
[![Build Status](https://travis-ci.com/githubfoam/ruby-role.svg?branch=badges)](https://travis-ci.com/githubfoam/ruby-role)  
Travis (.com) molecule travisci branch:
[![Build Status](https://travis-ci.com/githubfoam/ruby-role?branch=travisci)](https://travis-ci.com/githubfoam/ruby-role)  




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
