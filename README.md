# Ansible Role For AWS Cloudwatch

[![Current Version](http://img.shields.io/github/release/crushlovely/ansible-cloudwatch.svg?style=flat)](https://crushlovely/ansible-cloudwatch/releases)
Configures an AWS EC2 instance to send memory statistics to Cloudwatch.  This role assumes that you have provisioned your instance using an IAM role that has access to Cloudwatch.

## Installation

``` bash
$ ansible-galaxy install crushlovely.cloudwatch,v1.0.0
```


## Usage

Once this role is installed on your system, include it in the roles list of your playbook.

``` yaml
- hosts: localhost
  roles:
    - { role: crushlovely.cloudwatch }
```

## Dependencies

Standalone Role

## License

MIT