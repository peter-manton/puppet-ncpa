# Nagios Cross-Platform Agent

#### Table of Contents

1. [Description](#description)
1. [Usage - Configuration options and additional functionality](#usage)
1. [Limitations - OS compatibility, etc.](#limitations)
1. [Development - Guide for contributing to the module](#development)

## Description

Install the Nagios Cross-Platform Agent on RHEL. 

Based on work from gerapeldoorn (https://forge.puppet.com/gerapeldoorn)

## Usage

```puppet
include ncpa
```

Hiera:
```yaml
ncpa::community_string: 123413242134
```

## Limitations

Currently only works for RHEL 7.

I have plans to get this working older versions of RHEL as well as Debian.

## Development

https://github.com/peter-manton/puppet-ncpa

## Release Notes
## 0.3.0 Made upgrade possible for nagios package (added parameter)
