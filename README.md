# agentic-workflow-snow-tickets
This repo holds the high-level plan for building a workflow to solve ServiceNow tickets with an agentic AI workflow. 

The infrastructure underlying this workflow will be deployed and managed by Terraform Enterprise. The Agentic AI workflows will be secured by HashiCorp Vault Enterprise. 

Ticket resolution workflows will be driven by ServiceNow using idempotent Ansible Automation Platform for OS-level interaction and Terraform Enterprise for quick repaving or resource reaping.


## Resources to integrate

* [Terraform Enterprise deployment to EKS HVD](https://github.com/hashicorp/terraform-aws-terraform-enterprise-eks-hvd)
* [Vault on Kubernetes Official Helm Chart](https://developer.hashicorp.com/vault/docs/deploy/kubernetes)
* [Ansible and ServiceNow Demo by Jerry Corum](https://github.com/corumj/ansible-servicenow-demo)
