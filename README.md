# ansible-role-k8s-preparation

An Ansible Role prepares system requirements for k8s on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

```bash
sysctl_params:
  - name: net.bridge.bridge-nf-call-ip6tables
    value: "1"
  - name: net.ipv4.ip_forward
    value: "1"
  - name: net.bridge.bridge-nf-call-iptables
    value: "1"
```

Settings for sysctl.

## Dependencies

None.
