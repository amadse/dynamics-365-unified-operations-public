---
# required metadata

title: Develop and customize home page
description: This topic provides links to topics about development.
author: RobinARH
manager: AnnBe
ms.date: 10/16/2019
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer
# ms.devlang: 
ms.reviewer: rhaertle
ms.search.scope: Operations
# ms.tgt_pltfrm: 
ms.custom: 21631
ms.assetid: 06e26767-6056-4755-b47e-0bda71833581
ms.search.region: Global
# ms.search.industry: 
ms.author: rhaertle
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0

---

# Develop and customize home page

[!include [banner](../includes/banner.md)]

This topic provides links to topics about development.

## Overview

The Finance and Operations applications represent the next-generation enterprise resource planning (ERP) offering from Microsoft. It is designed to enable the entire ERP application suite as a cloud-based solution, for both public and private clouds, as well as on-premises. It leverages the speed, simplicity, and cost-effectiveness of working in the cloud, while building on the latest technology from Microsoft. This release introduces significant changes to the development experience. These changes include:

- Development tools that are decoupled from any running environment. You develop against local, XML-based files, not the online database.
- Microsoft Visual Studio is the development environment. The Visual Studio environment is customized to provide you with a smooth and familiar experience.
- The X++ compiler generates Common Intermediate Language (CIL) for all features. CIL is the same intermediate language used by other .NET-based (managed) languages, such as the C\# programming language.
- You can leverage the browser-based client and the design patterns for forms to provide an improved end-user experience.
- The Application Lifecycle Model (ALM) supports build automation, test automation, and deployment of models to the cloud.

## Architecture
-   [Application stack and server architecture](application-stack-server-architecture.md)

## Getting started
-   [Get evaluation copies](get-evaluation-copy.md)
-   [Sign up for preview subscriptions](sign-up-preview-subscription.md)
-   [Deploy and access development environments](../dev-tools/access-instances.md)
-   [Development system requirements](development-system-requirements.md)
-   [Removed or deprecated features](../migration-upgrade/deprecated-features.md)
-   [Deprecated APIs](../migration-upgrade/deprecated-apis.md)
-   [Rename a local development (VHD) environment](../migration-upgrade/vso-machine-renaming.md)
-   [Introduction to Azure DevOps (Video)](https://channel9.msdn.com/Events/Build/2014/2-575)
<!-- [Learn about packages, models and Visual Studio (Office Mix)](https://mix.office.com/watch/ies6lyit6773)-->
<!-- [Development tools performance tips (Office Mix)](https://mix.office.com/watch/rnp6ng9wu8kx)-->
<!-- [Feedback and support (Office Mix)](https://mix.office.com/watch/92azzna59jj6)-->

## Fleet Management
-   [Fleet Management sample application](introduction-fleet-management-sample.md)
-   [End-to-end scenario for the Fleet Management sample application](fleet-management-sample.md)

## Development tools
### Tutorials

-   [Development tools tutorial](introduction-visual-studio.md)
-   [Create models and data model elements overview](create-data-model-elements.md)
-   [Build and debug projects](build-debug-project.md)
-   [Version control, metadata search, and navigation](version-control-metadata-navigation.md)

### Tools, models, and VMs

-   [Development tools in Visual Studio](development-tools-overview.md)
<!-- [Introduction to the development environment (Office Mix)](https://mix.office.com/watch/1tz7194y62m3s)-->
-   [Application Explorer](application-explorer.md)
-   [Finance and Operations project type in Visual Studio](projects.md)
-   [Element designers](element-designers.md)
-   [Commands for determining how elements are used](element-usage.md)
-   [Models and packages](models.md)
-   [Build operations](build-operations.md)
-   [Code editor features](code-editor.md)
-   [Tools add-ins for Visual Studio](developer-tools-add-ins.md)
-   [Export and import models](models-export-import.md)
-   [Metadata search in Visual Studio](metadata-search-visual-studio.md)
-   [Create new users on development machines](enable-development-machine.md)
-   [Update the Visual Studio development tools](update-development-tools.md)
-   [Development and build VMs that don't allow admin access FAQ](../sysadmin/VMs-no-admin-access.md)
<!--  [Configure version control with Azure DevOps (Office Mix)](https://mix.office.com/watch/1ftubtqzp3xxl)-->

## X++ programming language
### Tutorials

-   [X++ and debugger features](new-x-debugger-features.md)
-   [Write business logic by using C\# and X++ source code](write-business-logic.md)

### Language support

-   [Changes in X++ and the X++ compiler](programming-language-support.md)
-   [EventHandlerResult classes in request or response scenarios](event-handler-result-class.md)
-   [Debug X++ code by using the debugger in Visual Studio](debug-xpp.md)
-   [Language Integrated Query (LINQ) provider for C\#(linq-provider-c.md)
-   [Write best practice rules](author-best-practice-rules.md)

### Reference

-   [X++ language reference](../dev-ref/xpp-language-reference.md)

## Customize with extensions and overlayering
- [Extensibility home page](../extensibility/extensibility-home-page.md)
- [Customize App Suite reports by using extensions](../analytics/customize-app-suite-reports-with-extensions.md)

## Code migration
- [How to resolve conflicts in Visual Studio (video)](https://youtu.be/4rxO0zUN2zU)
- [Code migration and upgrade home page](../migration-upgrade/code-migration-home-page.md)

## Move packages between environments
- [Create deployable packages of models](../deployment/create-apply-deployable-package.md)

## Performance
- [Take traces by using Trace parser](../perf-test/trace-trace-tutorial.md)
- [Diagnose issues and analyze performance by using Trace parser](../perf-test/trace-parser.md)
- [Performance timer](../perf-test/performance-timer.md)
<!-- [Expanding data with the Data Expansion tool (Office Mix)](https://mix.office.com/watch/11cet1u4nmn64)
- [Analyzing performance Issues with Trace Parser (Office Mix)](https://mix.office.com/watch/17d76cll0npyw)
- [The performance timer and other tools (Office Mix)](https://mix.office.com/watch/ij5cqidra5q3)
- [Using Task Recorder to create a single user performance test (Office Mix)](https://mix.office.com/watch/qtdlasy2rcf3)
- [The performance timer and other tools (Office Mix)](https://mix.office.com/watch/ij5cqidra5q3)
- [Analyzing performance Issues with Trace Parser (Office Mix)](https://mix.office.com/watch/17d76cll0npyw)-->

## User interface concepts
The client is an HTML web client that runs in all major browsers. For information about developing and customizing the user interface, see the [User interface development home page](../user-interface/user-interface-development-home-page.md).

## Analytics
- [Analytics, aggregate measurements, and KPI modeling](../analytics/analytics.md)

## Reporting services
- [Electronic reporting (ER) overview](../analytics/general-electronic-reporting.md)
<!-- [Introduction to Advanced Reporting Solutions (Office Mix)](https://mix.office.com/watch/wdl1dquy2tve)
- [Demo of Advanced Reporting Solutions (Office Mix)](https://mix.office.com/watch/1hkvtnc8sc7l6)-->

## Data entities and OData
- [Data entities overview](../data-entities/data-entities.md)
- [Open Data Protocol (OData)](../data-entities/odata.md)

## Testing support in Visual Studio
- [Testing and validations](../perf-test/testing-validation.md)
- [Test projects in Visual Studio](../perf-test/testing-support.md)
- [Developer topology deployment with continuous build and test automation](../perf-test/continuous-build-test-automation.md)
- [Task recorder resources](../user-interface/task-recorder.md)

## Office integration
- [Office integration overview](../office-integration/office-integration.md)

## Intelligence
- [Business intelligence (BI) and reporting home page](../analytics/bi-reporting-home-page.md)
<!-- [Overview of aggregate data (Office Mix)](https://mix.office.com/watch/16yvvnw45kzhf)-->

## Mobile platform
- [Mobile platform resources](../mobile-apps/platform/mobile-platform-home-page.md)

## Global finance management
- [Financials development home page](../financial/financial-dev-home-page.md)

## Licensing
- [Independent software vendor (ISV) licensing](isv-licensing.md)

## Supply Chain Management
- [Gantt control development guide](../user-interface/gantt-development-guide.md)
- [Create a new transportation management engine](../../../supply-chain/transportation/create-new-transportation-management-engine.md)

## Additional resources
[Insider tips on development](https://community.dynamics.com/ax/b/newdynamicsax)



