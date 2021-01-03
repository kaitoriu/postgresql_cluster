# postgresql_cluster
This is a tutorial on how to create a postgresql cluster using repmgr as a failover, pgpool-ii as a load balancer which splits tasks into each replica, and pgbouncer as a session to speed up connection to the database.

in this tutorial we will use 4 servers with Ubuntu Server 20.04, but you can use more servers base on what your need.
The servers we will use are for:
1. Postgresql master
2. Postgresql slave
3. Proxy server
4. Load balancer

