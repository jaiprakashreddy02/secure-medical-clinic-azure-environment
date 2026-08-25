# Secure Medical Clinic Azure Environment — Career Content

## Résumé bullets

- Designed a secure Azure portfolio environment using a three-tier VNet (web, app, and data subnets) with dedicated NSGs, least-privilege traffic rules, and no public RDP/SSH exposure.
- Hardened Azure Blob Storage using private containers, TLS 1.2, Microsoft Entra authorization, disabled Shared Key and anonymous access, seven-day soft delete, and selected-network restrictions.
- Implemented Microsoft Entra groups and scoped Azure RBAC for Contributor, Network Contributor, Storage Blob Data Reader, and Storage Blob Data Contributor access.
- Configured Azure Monitor Activity Log alerts and an email action group; validated detection through a controlled NSG change and successful notification.
- Applied Azure governance with tags, a deny policy, a resource-group delete lock, and an A$5 monthly budget; remediated policy and NSG configuration findings during security testing.

## LinkedIn project description

I built a **Secure Medical Clinic Azure Environment** as a hands-on portfolio project while developing my AZ-900 knowledge. The lab uses only fictitious data and demonstrates a three-tier virtual network, dedicated Network Security Groups, hardened Blob Storage, Microsoft Entra groups, scoped Azure RBAC, Activity Log alerts, email notifications, resource locks, Azure Policy, tags, and cost controls. I also tested expected-deny scenarios, corrected NSG and tagging issues, and documented the results as a security case study. No RDP or SSH was exposed to the internet, and the environment avoided high-cost gateway services and always-on compute.

#Azure #AZ900 #CloudSecurity #MicrosoftEntra #Cybersecurity #AzureMonitor #AzurePolicy

> Before posting, conceal subscription IDs, tenant/object IDs, emails, and personal information in every screenshot.