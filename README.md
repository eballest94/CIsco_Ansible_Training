# CIsco_Ansible_Training


Topology:

                       +------------------+
                       |   Controller     |
                       +--------+---------+
                                |
        +-----------------------+-----------------------+
        |                                               |
+-------+----------+                          +---------+--------+
|      lb01        |                          |        db01      |
+------------------+                          +------------------+


======== How to Install Ansible ========

Step 1 — Installing Ansible
$ sudo yum install epel-release
$ sudo yum install ansible
