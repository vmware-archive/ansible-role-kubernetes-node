# ansible-role-kubernetes_node

Ansible playbook to automate installing and maintaining kubernetes nodes.

## Requirements

This role currently requires a working VMware Photon server with enabled Docker environment.

## Role Variables

... forthcoming

## Example playbook

```
---
- hosts: kubernetes_nodes
  sudo: True
  roles:
    - kubernetes_node
  vars:
    - ... forthcoming
```

# License and Copyright
 
Copyright © 2015 VMware, Inc. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0 OR GPL-3.0-only

This code is Dual Licensed Apache License 2.0 or GPLv3

You may obtain a copy of the License(s) at

    http://www.apache.org/licenses/LICENSE-2.0

    or

    https://www.gnu.org/licenses/gpl-3.0.en.html
