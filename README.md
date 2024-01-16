# Ansible External Secure Access and Dynamic Inventory GCP

IAP allows for secure access to your resources located within your environment. After spinning up a vm instead of using a traditional SSH, IAP verifies user identity and the context of the request to determine if a user should be allowed access to the VM. Ansible allows for us to configure that connection while also standing up the infrasturce needed in a playbook.
![image](https://github.com/ohakawati/AnsibleExternalSecureAccessandDynamicInventoryGCP/assets/89810188/9dc78858-d651-400f-b39b-6f4e1ae8f6d3)
https://medium.com/google-cloud/gaining-secure-access-to-bastion-hosts-from-ansible-using-iap-7c92e7ebf4da
