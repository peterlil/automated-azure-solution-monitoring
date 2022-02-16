# Automated Azure Solution Monitoring
This repo will (hopefully) contain a simple starter solution that helps teams with getting an native Azure monitoring solution in place for their Azure workloads.

## Required Azure Services
Azure Service  | Purpose
---------------|---------------------------------------------------
Key Vault      | Keeps secrets and stuff.
Azure Function | Does inventory of the services in the subscription and stores the result in a Cosmos DB. It identifies with a Managed Identity and reads secrets from Key Vault.