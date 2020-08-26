# Ansible Role for Containers Common Configuration Files

## 4.6.0 - TBC

### Major Changes

  - Upgrade minimal Ansible Lint support to 4.3.2

## 4.5.0 - 2020-08-26

### Major Changes

  - Upgrade Travis CI test as Ubuntu Focal based
  - Upgrade minimal Ansible support to 2.10.0
  - Support openSUSE Leap 15.2
  - Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

  - Support `crun`
  - Support Fedora 32
  - Support Debian 10
  - `molecule -s default` with delegated to localhost

## 4.3.0 - 2020-04-22

### Major Changes

  - Template `molecule -s default` with dummy docker driver
  - Support CentOS/RHEL 8
  - Support Ubuntu 20.04
  - Remove Ubuntu 16.04 support
  - Split role as `skopeo` and `containers_common`

## 4.2.0 - 2020-04-03

  - Ininitial release for Ansible 2.9 or higher
  - Support both Ubuntu 16.04/18.04/19.10 or RHEL/CentOS 7 or openSUSE Leap 15.1
