# ansible-hdfs

An Ansible role for installing [Cloudera HDFS](http://www.cloudera.com/content/cloudera/en/products-and-services/cdh.html).

## Role Variables

- `hdfs_version` - HDFS version.
- `hdfs_conf_dir` - Configuration directory for HDFS (default: `/etc/hadoop/conf`)
- `hdfs_namenode` - Flag to determine if a node is an HDFS NameNode (default: `False`)
- `hdfs_namenode_host` - Hostname of the HDFS NameNode (default: `localhost`)
- `hdfs_namenode_port` - Port of the HDFS NameNode (default: `8020`)
- `hdfs_disks` - A list of disks available on the HDFS DataNodes (default: `[]`)

## Example Playbook

See the [examples](./examples/) directory.
