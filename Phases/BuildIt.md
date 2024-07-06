# Build it

> Build it and they will come.

---
Construction Phase

---

Students build a Linux server and install two different services on it (each service can only be installed X times during a given game).  They will have 2 weeks to do this.

## Build Options

All students will  [build an Ubuntu 20.04 server](https://github.com/Cyberwildcats/BuildersStarter/blob/main/activities/linux/install_ubuntu_server.md).

## Mandatory Build Options
All students will make these changes on their system

* Install an [SSH server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/ssh.md)
* Generate an [SSH keypair](https://www.sectigo.com/resource-library/what-is-an-ssh-key) for their user account
  - Post the contents of your `~/.ssh/id_rsa.pub` file as a comment in this [Github Issue (#4)](https://github.com/Cyberwildcats/Built-to-be-Owned/issues/4)
* Create an account called `coach`
  - Give `coach` [sudo privileges to root](https://phoenixnap.com/kb/how-to-create-sudo-user-on-ubuntu)
  - Add this public key to the `/home/coach/.ssh/authorized_keys` file:  
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDGFDwAYSURoe1GazRo9lFhr8xs7aUgnlNR+/N5u+oKu8FeNwwqz75E0uuYeRDOeVEcth1CVhwl+ZtJKvCkst4QvxS1zvqO8suKnQXUVQaoESREf05f03ugnkXrJjrKPp9RWUQMKfwUrGNgoOBQj8rW+y1xJo+jX6HPLecX3qgQWc/St/oiw37ur5My3C8/DrtL+ylkiK3dbkHjMSzUt1DRVWhNfIIBPYYrwCNecPCsI4TN56ehGFrpjvA9oDrtRG0bbxWoxGzGUyL9GbRfBalMECDmlXKvIk4ueF9lHX0VvMJheyC9vO+0knKwHjoDTga0Vo1eRz9ghqJ6H5am8ehYGq8G9QfI3k4P3ra6TGk8rFlnl182bKOatMYy6ttIEsuVlaAoVeyGB3MCf3mgzn6FN6Xb7oIC9QWBavAj5azdgM+4PCv0No5a0MtQ8umRHtn54tZ95aqsxPPbLhbJR8sM94DDxU365zbDO4USDad+St2aDC+j+twmiCBWAAk+d5s= earnoth@MacBookPro13.local
```

## Available Services 
Students will pick 2 services from the following list to install on their server.  

* [Apache web server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/apache.md)
* [Postfix mail server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/postfix.md)
* [Samba SMB file server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/samba.md)
* [MySQL database server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/mysql.md)
* [Postgresql database server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/postgres.md)
* [BIND DNS server](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/bind.md)
* [Network File System (NFS)](https://github.com/Cyberwildcats/BuildersStarter/tree/main/activities/linux/services/nfs.md)

When you have chosen, post a comment to [this Github Issue](https://github.com/Cyberwildcats/Built-to-be-Owned/issues/5) to declare which two you are installing.