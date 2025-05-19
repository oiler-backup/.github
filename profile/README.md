# What is that ❔
Oiler is a fully open-source solution that allows you to set up automated backups of various databases inside and outside the Kubernetes cluster.
In addition to backup, it also provides functionality for restoring from a backup, including in automatic mode.
All interaction is built around the concept of Custom Resources in Kubernetes.

# What do we have now ❔
Currently, the following database types are supported:

- PostgreSQL
- MySQL
- MongoDB

Moreover, you can use our [CLI](https://github.com/oiler-backup/cli) to simlify interraction with adapter.
