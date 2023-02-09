# github-action-terraform-fmt

A simple Github Action which runs when a Pull Request is opened, to verify if any Terraform changes are formatted correctly.

Once the Action has ran, a summary is generated to clearly tell the user which Terraform files need to be ran under `terraform fmt`. 

This is a quick way to ensure that all your Terraform code is formatted, before merging into main.
