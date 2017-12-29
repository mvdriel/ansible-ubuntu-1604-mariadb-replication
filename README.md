## ubuntu-1604-mariadb-replication

#### Variables

* `ubuntu_1604_mariadb_replication_server_id`: [required]: Server-id

* `ubuntu_1604_mariadb_replication_user_name`: [optional, default `replicator`]: Username of the replication user
* `ubuntu_1604_mariadb_replication_user_password`: [required]: Password of the replication user

#### Examples

##### Minimal (set server-id and password of replication user only)

```yaml
---
- hosts: all
  roles:
    - ubuntu-1604-mariadb-replication
  vars:
    ubuntu_1604_mariadb_replication_server_id: '1'
    ubuntu_1604_mariadb_replication_user_password: 'this-is-a-test-password'
```
