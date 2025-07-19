<p align="center">
  <img src="images/2plus2cabbage.png" style="display: block; margin: 0; padding: 0;">
</p>

#### Let's learn about cool topics in technology together.  We'll start out with Terraform and see how things evolve from there.
- I am not an expert, nor do I claim to be.
- The only thing I am an expert in is my own opinion - and sometimes that is flawed.
- I do stupid things.
- Sometimes I figure out they are stupid.
- Sometimes you will, please be kind.

## 🗂️ Repositories

### Base Terraform Projects
- [terraform-aws-base](https://github.com/2plus2cabbage/terraform-aws-base) • Terraform base AWS deployment with a Windows Instance
- [terraform-azure-base](https://github.com/2plus2cabbage/terraform-azure-base) • Terraform base Azure deployment with a Windows Instance
- [terraform-gcp-base](https://github.com/2plus2cabbage/terraform-gcp-base) • Terraform base GCP deployment with a Windows Instance
- [terraform-oci-base](https://github.com/2plus2cabbage/terraform-oci-base) • Terraform base OCI deployment with a Windows Instance

### IPsec Connectivity Between Clouds

#### Azure to/from GCP
- [terraform-azure-to-gcp](https://github.com/2plus2cabbage/terraform-azure-to-gcp) • Connect Azure to GCP using IPsec with Terraform  
- [terraform-gcp-to-azure](https://github.com/2plus2cabbage/terraform-gcp-to-azure) • Connect GCP to Azure using IPsec with Terraform  

#### OCI to/from AWS
- [terraform-oci-to-aws](https://github.com/2plus2cabbage/terraform-oci-to-aws) • Connect OCI to AWS using IPsec with Terraform  
- [terraform-aws-to-oci](https://github.com/2plus2cabbage/terraform-aws-to-oci) • Connect AWS to OCI using IPsec with Terraform

### Palo Alto Firewall Deployment

#### OCI
- [terraform-oci-paloalto-base](https://github.com/2plus2cabbage/terraform-oci-paloalto-base) • Deploy a Palo Alto Firewall to OCI  
- [terraform-oci-paloalto-ha](https://github.com/2plus2cabbage/terraform-oci-paloalto-ha) • Deploy Palo Alto Firewalls with High Availability (HA) to OCI (failover performance is surprisingly not bad.  Failover is almost as fast as hardware firewalls.)

#### Azure
- [terraform-azure-paloalto-base](https://github.com/2plus2cabbage/terraform-azure-paloalto-base) • Deploy a Palo Alto Firewall to Azure  
- [terraform-azure-paloalto-ha](https://github.com/2plus2cabbage/terraform-azure-paloalto-ha) • Deploy Palo Alto Firewalls with High Availability (HA) to Azure (failover performance is meh.  Failover takes too long for production workloads.) **COMING SOON** Load Balancer Sandwich!

#### AWS
- terraform-aws-paloalto-ha • **COMING SOON** Deploy Palo Alto Firewalls with High Availability (HA) to AWS

#### GCP
- terraform-gcp-paloalto-ha • **NOT COMING SOON** Deploy Palo Alto Firewalls with High Availability (HA) to GCP - GCP requires load balancers so traditional HA doesn't work.  **COMING SOON** Load Balancer Sandwich!

---
## Cloud Account Setup Instructions
- [aws-account-terraform](https://github.com/2plus2cabbage/cloud-setup-docs/blob/main/aws-account-terraform.md) • Create an account to use Terraform with AWS
- [azure-account-terraform](https://github.com/2plus2cabbage/cloud-setup-docs/blob/main/azure-account-terraform.md) • Create an account to use Terraform with Azure
- [gcp-account-terraform](https://github.com/2plus2cabbage/cloud-setup-docs/blob/main/gcp-account-terraform.md) • Create an account to use Terraform with GCP
- [oci-account-terraform](https://github.com/2plus2cabbage/cloud-setup-docs/blob/main/oci-account-terraform.md) • Create an account to use Terraform with OCI

## 🙌 Contributions Welcome

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request.

---