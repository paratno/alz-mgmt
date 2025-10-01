# Azure Landing Zones Accelerator Starter Module for Terraform - Azure Verified Modules Complete Multi-Region

This module is part of the Azure Landing Zones Accelerator solution. It is a complete multi-region implementation of the Azure Landing Zones Platform Landing Zone for Terraform.

It deploys a hub and spoke virtual network or Virtual WAN architecture across multiple regions.

The module deploys the following resources:

- Management group hierarchy
- Azure Policy definitions and assignments
- Role definitions
- Management resources, including Log Analytics workspace and Automation account

## Usage

The module is intended to be used with the [Azure Landing Zones Accelerator](https://aka.ms/alz/acc). Head over there to get started.

>NOTE: The module can be used independently if needed. Example `tfvars` files can be found in the `examples` directory for that use case.
