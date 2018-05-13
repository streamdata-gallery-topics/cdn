---
name: Azure CDN
description: Ensuring a consistent user experience is important. If your websites
  or mobile apps involve streaming media, gaming software, firmware updates (Smart
  TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content Delivery
  Network helps you reduce load times, save bandwidth, and increase responsiveness.
image: ""
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Microsoft
- CDN
created: "2018-05-13"
modified: "2018-05-13"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/cdn/master/_listings/azure-cdn/apis.md
specificationVersion: "0.14"
apis:
- name: Azure CDN API Profiles List By Resource Group
  description: Lists all of the CDN profiles within a resource group.
  image: ""
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: http:://management.azure.com//
  tags: CDN
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/cdn/master/_listings/azure-cdn/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-cdn-profiles-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/cdn/master/_listings/azure-cdn/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-cdn-profiles-get-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cdn/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cdn/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cdn/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---