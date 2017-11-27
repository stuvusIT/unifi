# unifi

This role installs the ubiquiti unifi controller software.

## Requirements

Ubuntu

## Role Variables

| Name                      | Default | Description                                                                                                                                                                              |
|---------------------------|:-------:|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `unifi_system_properties` | `{}`    | Dict of settings to write to system.properties. See the [documentation](https://help.ubnt.com/hc/en-us/articles/205202580-UniFi-system-properties-File-Explanation) for more information |

## Example Playbook

```yml
- hosts: wifi
  roles:
    - unifi
      unifi_system_properties:
        unifi.http.port: 8000
```

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).


## Author Information

- [Janne Heß](https://github.com/dasJ)
