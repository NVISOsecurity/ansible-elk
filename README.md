# ansible-elk

An Ansible role for installing and configuring Elasticsearch, Logstash and Kibana

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Install ELK
  import_role:
    name: ansible-elk
```

## Disclaimer

This role is for use in the SANS 699 course and is provided as is.

## License

MIT / BSD