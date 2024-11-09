# Welcome
In this repository,  you can find different projects that are related to Blogs that I'm publishing 

## Join to domain
This is an Ansible playbook that connects a Linux server to a Windows Active Directory using secure or none secure LDAP

**Link to the blog:** https://medium.com/@dudu.zbeda_13698/how-to-connect-securely-ldaps-your-linux-server-in-windows-active-directory-aeaf41b66c49

**Steps for running this playbook:**
1. Create a server that includes ansible service. 
2. Download the playbooks from my git.
3. Update the "input-join-to-domain.yml" file with your environment configuration. Instruction can be found inside the file. 
4. Update the hosts file with your Linux server IP
5. In case you want to use a secure connection, generate a public certificate and copy it to the server from where you are running the Ansible playbook. The file name and path need to be defined in "input-join-to-domain.yml"
6. To execute the playbook, run "ansible-playbook -i hosts run-join-to-domain.yml"
    A. Once  executed you will need to enter the password for the domain user that you have defined in the "input-join-to-domain.yml" file.



**Linkedin profile:**   https://www.linkedin.com/in/davidzbeda
