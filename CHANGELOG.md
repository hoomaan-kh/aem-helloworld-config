# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed
- Update Jumphost access security group (from jumphost inbound to instances) with the resource `shn-awsres-03`
- Changed AEM JDK installation method


### Removed
- Removed `inbound_from_bastion_host_security_group` configuration since it's no longer needed in aem-aws-stack-builder 4.34.0
