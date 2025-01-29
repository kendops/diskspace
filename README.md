Before building an Ansible Tower (AWX) implementation for a customer, it's crucial to gather requirements to ensure a smooth deployment and alignment with their infrastructure and automation needs. Here are key questions to ask:

1. Business & Use Case Requirements
What are your primary use cases for Ansible Tower? (e.g., configuration management, application deployment, patching, security compliance, etc.)
What problems are you trying to solve with Ansible Tower?
What are the key business goals for implementing automation?

3. Infrastructure & Environment
What operating systems and distributions do you need to manage? (e.g., RHEL, Ubuntu, Windows, etc.)
What cloud providers or on-prem infrastructure do you use? (AWS, Azure, GCP, VMware, bare metal, etc.)
How many servers/nodes will Ansible Tower manage?
Are you using containers or Kubernetes? Do you need Ansible Tower to integrate with them?

5. Security & Compliance
Do you have security policies that Ansible Tower must adhere to? (e.g., RBAC, encrypted credentials)
What authentication mechanisms do you use? (LDAP, Active Directory, SAML, OAuth)
Do you require Role-Based Access Control (RBAC) to restrict access to playbooks and inventories?
Will there be privileged operations requiring integration with vaults (e.g., CyberArk, HashiCorp Vault)?

https://infotechys.com/install-ansible-tower-on-rhel-9/
