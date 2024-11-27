## chrome

[![CI](https://github.com/Oefenweb/ansible-chrome/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-chrome/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-chrome-blue.svg)](https://galaxy.ansible.com/Oefenweb/ansible-chrome)

Set up [Google Chrome](https://www.google.com/chrome/) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)
* `wget` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.chrome
```

#### License

BSD

#### Author Information

Mischa ter Smitten (based on work of [Chris Prescott](https://github.com/cmprescott))

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-chrome/issues)!
