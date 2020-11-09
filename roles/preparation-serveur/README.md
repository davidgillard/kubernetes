Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

Host kubmaster                                                                                                                              [444/1851]
  HostName 127.0.0.1                                                                                                                                  
  User vagrant                                                                                                                                        
  Port 2200                                                                                                                                           
  UserKnownHostsFile /dev/null                                                                                                                        
  StrictHostKeyChecking no                                                                                                                            
  PasswordAuthentication no                                                                                                                           
  IdentityFile /home/david/Documents/kubernetes/creation-cluster/kubernetes/creation-cluster/Plusieurs_serveurs/.vagrant/machines/kubmaster/virtualbox/private_key                                                                                                                                          
  IdentitiesOnly yes                                                                                                                                  
  LogLevel FATAL                                                                                                                                      
                                                                                                                                                      
Host kubnode                                                                                                                                          
  HostName 127.0.0.1                                                                                                                                  
  User vagrant                                                                                                                                        
  Port 2201                                                                                                                                             UserKnownHostsFile /dev/null                                                                                                                        
  StrictHostKeyChecking no                                                                                                                            
  PasswordAuthentication no                                                                                                                           
  IdentityFile /home/david/Documents/kubernetes/creation-cluster/kubernetes/creation-cluster/Plusieurs_serveurs/.vagrant/machines/kubnode/virtualbox/p
rivate_key                                                                                                                                            
  IdentitiesOnly yes                                                                                                                                  
  LogLevel FATAL                                                                                                                                      
                                                                                                                                                      
Host kubnode2                                                                                                                                         
  HostName 127.0.0.1                                                                                                                                  
  User vagrant                                                                                                                                          Port 2202                                                                                                                                           
  UserKnownHostsFile /dev/null                                                                                                                          StrictHostKeyChecking no                                                                                                                            
  PasswordAuthentication no                                                                                                                             IdentityFile /home/david/Documents/kubernetes/creation-cluster/kubernetes/creation-cluster/Plusieurs_serveurs/.vagrant/machines/kubnode2/virtualbox/
private_key                                                                                                                                           
  IdentitiesOnly yes                                                                                                                                  
  LogLevel FATAL