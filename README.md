# I create three containers and built automation with ansible 

![](/images/Graph.png)

## Table of Contents

1. [Create containers](#1-i-created-three-containers-in-docker)
2. [Create Network](#2-created-network-for-containers)
3. [Set up ssh](#3-install-ssh-or-open-ssh)
4. [Set up ssh keys](#4-enter-server1-and-create-ssh_key-after-then-copy-this-key-to-server2-and-server3)
5. [Check keys](#5-check-keys)
6. [Install Ansible and run](#6-install-ansible-on-the-server1-and-check)
7. [Create Playbook](#7-create-playbook-for-reboot-every-server)

- - -

### 1. I created three containers in Docker
![](/images/CreateContainers.png)
### 2. Created network for containers
![](/images/CreateNetwork.png)
### 3. Install ssh or open ssh 
![](/images/WriteToolForSetUpSsh.png)
![](/images/RunSshTool.png)
### 4. Enter server1 and create ssh_key after then copy this key to server2 and server3
![](/images/EnterServer1AndCreateSshKey.png)
![](/images/installpackegandcopykeytoservers.png)
### 5. Check Keys
![](/images/MakeSureThatKeysAreCopy.png)
### 6. Install Ansible on the server1 and check
![](/images/InstallAnsible.png)
![](/images/SetUpAnsibleFiles.png)

ansible.cfg file:

![](/images/ConfigFile.png)

hosts.yml file:

![](/images/HostYmlFile.png)

![](/images/InstallPytonInTheTwoServer.png)
![](/images/PingForCheck.png)
![](/images/Updateservers.png)
### 7. Create Playbook for reboot every server
![](/images/RebootFile.png)
![](/images/RunRebootPlayBook.png)
There is error because in the docker conteiner doesn't have kernel so there is no way to reboot our containers