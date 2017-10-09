# MySQL Asynchronous Replication

This template provides MySQL cluster with asynchronous replication.

## Notes
- MySQL cluster must consist of 2 nodes(1 master and 1 slave).
    - This template doesn't offer multi-slaves.
- When the replication fails to start, restart the master/slave-sidekick container.