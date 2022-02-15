# Common settings role
This role provides a means for all sorts of small tasks to configure certain aspects of systems.

NOTE: This is only meant for _small_ things! If a certain configuration aspect becomes too complex/big,
it should be moved to it's own role.

## Usage
* Create a new file in the ```tasks``` folder, example ```my_task.yml```
* Add a new setting to the host/group in the inventory like below
```
myhost_common_settings__to_merge:
  - 'my_task'
```
* Run Ansible
