<p align="center">
<img src="https://s3.amazonaws.com/classic.isaaguilar.com/terraform-operator-logo.gif" alt="Terraform Operator"></img>
</p>

> A Kubernetes CRD and Controller to handle Terraform operations by generating k8s jobs catered to perform Terraform workflows

<hr/>

## What is terraform-operator?

This project is:

- A way to run Terraform in Kubernetes by defining Terraform deployments as Kubernetes manifests
- A controller that configures and starts [Terraform Workflows](#link-tbd) when it sees changes to the Kubernetes manifest
- Workflow runner pods that execute Terraform plan/apply and other user-defined scripts

This project is not:

- An HCL to YAML converter or vice versa
- A Terraform Module or Registry


## Docs

Visit [http://tf.isaaguilar.com](http://tf.isaaguilar.com) for docs for version >= `v0.5.x`.
