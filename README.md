# AzureLightHouse

Azure Lighthouse enables multi-tenant management with scalability, higher automation, and enhanced governance across resources.

Azure Lighthouse will support Insight to be more responsive and efficient whilst providing you transparency into Insight’s access and the actions we take. Azure Lighthouse also enables you to have more a granular access management experience across your Azure estate. All without sacrificing any of the existing controls and visibility client currently have over who has access to your environment and individual resources. 

This repository holds the code to perform Azure Lighthouse enablement for Insight Azure Guardian deployments.

![design](./Image/Azure%20Lighthouse%20design.jpg)

Steps to perform Azure Lighthouse deployment

## Pre-requisites

1. User account running this script should have owner permission on the root azure management group.

## Steps

1. Open Cloudshell
2. Git clone https://github.com/Insight-Services-APAC/ms-azurelighthouse.git
3. cd ms-azurelighthouse
4. ./Deploy-AzureLighthouse.ps1
5. Add Management Group Name, Guardian Subscription Id, Guardian RG name, Region, and Country on prompt
6. For "Region" prompt use the appropriate region. (ie., australiaeast, australiasoutheast,etc.,)
7. For "Country" enter the following based on the selection below
- AU for Australia
- NZ for New Zealand
- US for North America
8. For Delivery, if Azure Guardian will be delivered globally enter "global" if within region enter "restricted"
