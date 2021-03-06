# Release Log: Ansible Collection - OS Hardening

## What's new 1.0.0

- Finished merging RHEL8/CentOS8 support
- Added RHEL9/CentOS9 support
- Added Ubuntu20.04 support
- Added Ubuntu18.04 support
- Added Debian 10 support
- Added Debian 9 support (CIS sections might mismatch the official document)
- Removed obsolete default variables from original role
- Added collection README
- 

## What's new 0.1.0

- Converted [CIS RedHat Enterprise Linux 7 Benchmark](https://github.com/ansible-lockdown/RHEL7-CIS) into an Ansible collection.
- Renamed rhel7_cis role into linux_cis role
- Refactored linux_cis to have variable based Section numbers
- Refactored linux_cis to be distribution-agnostic and able to be extended with any number of distributions.
- Added support for RHEL8/CentOS8 to linux_cis role (doesn't fault but not all CIS benchmarks included)
- Made filtering for CIS sections based on open-ended list of strings rather than individual variables
- Allowed filtering of CIS sections based on section name
