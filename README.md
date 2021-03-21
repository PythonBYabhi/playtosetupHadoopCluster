# playtosetupHadoopCluster
Here I am publishing an ansible playbook, which can be easily used to setup hadoop cluster

## How To Use This Repo

Step 1:- Clone this repo in your system.

Step 2:- Install Ansible in your system using pip or package installer.

### pip install ansible 


step 3:- Go inside the cloned repo and add the IP's of node on which you want to setup Cluster.

step 4:- Add the path to ssh key in ansible.cfg file for all the nodes.

step 5:- run the following command in your repo..

#### ansible-playbook hadoop.yml


It will ask you to enter the ip of namenode, enter the ip of the node on which it will setup the Namenode for Hadoop Cluster.

And, Your Cluster will be launched.


Thanks for viewing this Repo. 

If you find it useful add a star to it.
