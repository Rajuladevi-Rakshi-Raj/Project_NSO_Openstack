# Project_NSO_Openstack
#prerequisites
-ansible 2.9.6
-python version = 3.8.10
-openstack 5.2.0 
-jq-1.6

The project solution consists of three operating modes; deployment, operations, and cleanup.  Access to the cloud is via an openrc file with the required credentials to access a specific cloud. At the time of deployment, the solution should use a TAG to attach to all items it creates within the OpenStack Cloud, as to enable easy identification of things 
To run the code we use the fllowing commands 

1)./install openrc tag ssh_key    
2)./operate openrc tag ssh_Key                    
3)./cleanup openrc tag ssh_Key

openrc refers to a file containing your own rc file with reqired credentials.
The parameter ssh_key refers to a file containing a public key. This key file is used for secure authentication and communication with remote systems. Ensure that the specified ssh_key file contains the public key of your local computer (Ubuntu).
