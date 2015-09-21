[pangu-zookeeper]
host-10-2-0-17 ansible_ssh_host=192.168.173.25 ipv4_addr=192.168.173.25 pangu_zookeeper_myid=1
host-10-2-0-18 ansible_ssh_host=192.168.173.26 ipv4_addr=192.168.173.26 pangu_zookeeper_myid=2

[pangu-storm]
host-10-2-0-17 storm_nimbus_enabled=true storm_supervisor_enabled=false
host-10-2-0-18 storm_supervisor_enabled=true storm_nimbus_enabled=false

[pangu-redis]
host-10-2-0-17
