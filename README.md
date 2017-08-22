# Demo for a docker Images build host

# Setup

1 - create inventory with group local  just with *localhost*
```
[local]
localhost

```

2 - setup images to be build in the var *docker_builder* (check examples  in group_vars/local/main.yml )

# Usage (sudo permissions are required )

```bash
ansible-playbook  -i inventory/myinventory  playbooks/build.yml
```

# License

GPL 3.0

# Author Information

Created by Miguel Rodrigues.
