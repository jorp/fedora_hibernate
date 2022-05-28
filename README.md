# fedora hibernate

use this playbook to configure fedora 33+ default btrfs + zram layout for hibernation by adding a swapfile

see my blog post about this topic [here](https://jorp.xyz/posts/fedora-btrfs-and-hibernation/)

### instructions

- set `swapfile_path` var to desired swapfile location

```bash
ansible-galaxy collection install containers.podman
ansible-playbook playbook.yml -K
```
