[![collection l3d.voc](https://ansible.l3d.space/svg/l3d.voc_ansible-collection_collection.svg)](https://galaxy.ansible.com/ui/repo/published/l3d.voc/)
[![Maintainance](https://ansible.l3d.space/svg/l3d.voc_maintainance_collection.svg)](https://ansible.l3d.space/#l3d.voc)
[![License](https://ansible.l3d.space/svg/l3d.voc_license_collection.svg)](LICENSE)

 Ansible Collection - l3d.voc
============================

This is the Ansible Collection ``l3d.voc``. A collection to setup and configure a linux based OBS-Studio VOC Setup for [CWTV](https://chaoswest.tv) and [winkekatze.tv](https://winkekatze.tv).

## Ansible Roles in l3d.voc
tbd.

## Warning
This ansible collection is in early development. It will probably change!

## Using this Collection
You can install the collection using ansible-galaxy by running:
```bash
ansible-galaxy collection install l3d.voc:1.0.0
```

Remember you can to Upgrade to the latest version of the l3d.voc collection using the ``--upgrade`` parameter:
```bash
ansible-galaxy collection install l3d.voc --upgrade
```


Or you could clone this collection in your local ansible project for example to ``collections/ansible_collections/l3d.voc/``. Make sure you checkout [git submodules](https://git-scm.com/docs/git-submodule) too. Example:
```
# Clone git Repo with submodules to specified path
git clone --recursive https://github.com/roles-ansible/ansible_collection_voc.git collections/ansible_collections/l3d/voc/

# change directory
cd collections/ansible_collections/l3d.voc/

# optionally init git submodules
git submodule update --init --recursive

# optionally install all requirements
ansible-galaxy collection install -r requirements.yml --upgrade
```

You can also list a collection in ``requirements.yml``:
```yaml
---
collections:
  - name: l3d.voc
    version: ">=1.0.0"
```
