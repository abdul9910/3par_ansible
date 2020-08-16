# HPE 3PAR and HPE Primera modules for Ansible <h1>

### The HPE 3PAR and HPE Primera modules for Ansible enable automation of storage provisioning for the HPE 3PAR and HPE Primera array. 
### The modules use the HPE 3PAR and HPE Primera SDK for Python to communicate with the storage array over the WSAPI REST interface.<h2>

# Requirements  <h1>

* Ansible ver. 2.5, 2.6, 2.7, 2.8
* hpe3par_sdk
* 3PAR OS
* 3.3.1 MU1, MU2, MU3, T05
* 3.2.2 MU4, MU6
* Primera OS
* 4.0.0

# Configuration <h1>

* Install Ansible and hpe3par_sdk
* Modify ansible.cfg file to point the library to the Modules folder

> Library=/home/user/workspace/hpe3par_ansible/Modules 
