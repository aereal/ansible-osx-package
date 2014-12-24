# ansible-osx-package

Build Python and Ansible for bootstrap (unofficial)

## Description

The repository provides pre-built Python and Ansible packages for bootstrapping OS X machines with Ansible.

### Problem

To Configure Mac OS X with Ansible, we face the problem about **“how to install Ansible”**.

There are some choices such as:

* Install to system Python
* Install to another Python installation (maybe include *how to install Python* problem)

### Solve

Install pre-built Python and Ansible from tarball.

## Install

Downloads a tarball from [releases][releases], then:

```sh
cd /
tar xjf $tarball_path
```

[releases]: https://github.com/aereal/ansible-osx-package/releases
