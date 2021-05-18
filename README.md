# vagrant-centos7-cockroachdb



## Summary

I'm following some cockroachDB courses:
* April 2021 - https://university.cockroachlabs.com/course/introduction-to-distributed-sql-and-cockroachdb
* May 2021 - https://university.cockroachlabs.com/course/practical-first-steps


Below I also show how to setup a centos7-cockroachDB virtualbox-vm via vagrant i.e. as well as my notes on working through the cockroachlabs training/university materials.


## More Details 

### April 2021 

https://university.cockroachlabs.com/course/introduction-to-distributed-sql-and-cockroachdb

* [Base Vagrant Setup (running centos7 cockroachdb v20.2.7) - notes and key points](docs/Base-Vagrant-Setup.md)
* [Exploring demo db - shipped with cockroach](docs/demo_db.md)
* [Introducing the cockroach web-console](docs/Introducing-web-console.md) 


### May 2021 

https://university.cockroachlabs.com/course/practical-first-steps

* [Transaction management and TransactionAbortedError](docs/Transaction_management.md)
* [Explain plans & secondary indexes](docs/Explain_plans-and-secondary_indexes.md)
* [Starting an Insecure Single-Node Cluster and sample movr datbase](docs/Start-an-Insecure-Single-Node-Cluster.md)
* [Stopping and Removing a Local CockroachDB Cluster via pkill plus data & log files](docs/Stopping-Local-Cockroach-via-pkill.md)
* [Basic CSQL DDL: CREATE & SET database - CREATE & ALTER table - SHOW CREATE](docs/CREATE_SET_DATABASE-CREATE_ALTER_TABLE.md)
* [Introducing web-console part2 - simple load test OLTP vs OLAP on distinct nodes](docs/Introducing-web-console-part2.md)
* [Cluster Concepts: Keyspace-Ranges-Replicas (cover a few key concepts - documentation only)](docs/Cluster-Concepts_Keyspace-Ranges-Replicas.md)
* [Automation to create haproxy for cluster: cockroach gen haproxy ](docs/cockroach-gen-haproxy.md)
* [Starting a 6 node cluster and dead-node rebalancing](docs/6node-cluster-dead-node-rebalanced.md)
