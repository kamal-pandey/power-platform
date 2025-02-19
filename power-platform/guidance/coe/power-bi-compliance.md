---
title: "Review compliance and adoption statistics with the CoE Power BI dashboard | MicrosoftDocs"
description: "The Compliance and Adoption Power BI dashboard gives you the ability to review compliance, security and governance statistics and gain further adoption insights."
author: manuelap-msft
manager: devkeydet

ms.component: pa-admin
ms.topic: conceptual
ms.date: 06/01/2021
ms.subservice: guidance
ms.author: mapichle
ms.reviewer: jimholtz
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---
# Compliance and Adoption with the CoE Power BI dashboard

>[!IMPORTANT]
> The reports on this page are part of a separate dashboard, **PowerPlatformGovernance_CoEDashboard_MMMYY.pbit**. See: [Setup Power BI dashboard](setup-powerbi.md).

The **Compliance and Adoption** dashboard highlights governance, compliance and security insights, allows you to gain a high level view into your adoption and provides a tech debt report of the [Default environment](/power-platform/admin/environments-overview#the-default-environment).

## Compliance and Governance

The **Compliance and Governance insights** page provides you with a tenant-wide overview of:

- Apps and flows without an owner
- Apps and flows not in solutions
- Apps and flows with duplicate names
- Apps and flows with test, demo, template in the name
- Apps and flows with open [compliance details requests](example-processes.md)
- Apps currently not compliant with DLP policies or billing policies
- Grandfathered apps
- Apps shared with everyone and apps shared with more than 100 users
- Apps not launched in the last month and in the last quarter
- Suspended flows
- Flows using plain text passwords
- Cross-tenant connections
- Environments with no apps or flows

![Compliance and Governance insights.](media/pbi-compliance1.png "Compliance and Governance insights")

From each card, you can drill-through to a list of apps or flows matching the selected criteria:

![Compliance and Governance drill-through.](media/pbi-compliance2.png "Compliance and Governance drill-through")

## Adoption insights

The **Adoption insights** page provides you with a tenant-wide overview of:

- Apps launched this month and this quarter
- Unique users in the past month
- Total makers
- Top 5 connectors used in apps and flows
- Top 5 most launched apps
- Top 5 makers with the most launched apps
- Top 5 countries where makers create most launched apps
- Top 5 environments that consume the most capacity

![Adoption insights.](media/pbi-compliance1.png "Adoption insights")

## Default environment

The **Default environment** page gives you an overview of adoption in the default environment, with the intent to help clean up tech debt in this environment and highlight highly adopted resources that may need to be migrated to a production environment.

- Apps and flows without an owner
- Apps currently not compliant with DLP policies or billing policies
- Grandfathered apps
- Apps shared with everyone and apps shared with more than 100 users
- Suspended flows
- Flows using plain text passwords
- Top 5 most launched apps
- Top 5 most shared apps
- Latest non-compliant apps
- Latest suspended flows

![Default environment tech debt insights.](media/pbi-compliance1.png "Default environment tech debt insights.")
