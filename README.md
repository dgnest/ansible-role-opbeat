# Ansible Role ansible-role-opbeat

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-opbeat.svg)](https://travis-ci.org/dgnest/ansible-role-opbeat)
[![Stories in Ready](https://badge.waffle.io/dgnest/ansible-role-opbeat.svg?label=ready&title=Ready)](http://waffle.io/dgnest/ansible-role-opbeat)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-opbeat.svg)](https://github.com/dgnest/ansible-role-opbeat/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


This Ansible Role infuses antigravity, you are warned

Install it with the following command:

```bash
$ ansible-galaxy install dgnest.opbeat

```
Requirements
------------

None



## Role Variables

Here is the list of all variables and their default values:

```yaml
    ---
    # defaults file for dgnest.opbeat
    opbeat_organization_id: ''
    opbeat_app_id: ''
    opbeat_secret_token: ''
    opbeat_project_path: ''
```


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

```yaml
    - hosts: servers
      roles:
        - dgnest.opbeat
```


## License

MIT

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [author][link-author]
- [All Contributors][link-contributors]


---

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS
[link-company]: https://github.com/dgnest