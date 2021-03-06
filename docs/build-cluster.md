# Build the Kubernetes cluster

## 1. Create Infrastructure

Before executing Terraform you need to obtain your Digital Ocean token [here](https://cloud.digitalocean.com/settings/api/tokens)

To see the changes which are going to be made execute the following commands:

Note: You will need to paste in the Digital Ocean Token during the Terraform execution.

```
$ cd terraform
$ terraform plan
```

To apply the changes execute the following commands:

```
$ terraform apply
```

## 2. Provisioning the Kubernetes cluster using Kismatic

To provision the cluster follow the steps [here](accessing-the-bootstrap-node.md)