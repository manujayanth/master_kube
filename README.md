# master_kube
To create a Kubernetes Master node over AWS using ansible

1. Add the aws access key and secret key

2. Create the key and value pair(tag_name) for Masternode such as --Name:MasterKube

3. Create the key and value pair(tag_name) for Slavenodes such as --Name:SlaveKube

4. Run the master.yml playbook and will generate the token automatically and store in /root directory

5.Run the slave.yml playbook and it will automatically use the token generated by master

Note: Run the Masternode playbook before running the slavenode playbook and change the current location of master.yml or slave.yml before running
