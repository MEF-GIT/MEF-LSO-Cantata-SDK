# MEF-LSO-Cantata-SDK - Aretha Release

## Download Link

Download the entire repository by clicking
[here](https://github.com/MEF-GIT/MEF-LSO-Cantata-SDK/releases/download/aretha/MEF-LSO-Cantata-SDK-aretha.zip)

## Overview

This repository contains the MEF LSO Cantata SDK. It includes API definitions for the following functional areas to support Subscriber Ethernet Products (EPL) leveraging the corresponding Sonata API specifications:

- Product Order

The Subscriber Ethernet Product Specification for EPL leverages and builds on top of the Product Specification for Access ELine as delivered by MEF W106. Static binding of Product Order envelope API with EPL Product Specification payload is also provided

## Maturity Level

The API files contained in this SDK are evolving and subject to change. They are based on documents that are either ratified standards or draft standards that have not yet completed the review cycles and approvals necessary to achieve the status as a MEF standard. MEF is making these publicly available at this time to invite wider industry review.

The maturity per functionality presents as follows:

- Order:
  - Business Requirements - MEF 57.2 - **Draft Release 1**
  - Developer Guide - **none**
  - API - **work in progress**

## Contents

This SDK contains the following items:

- `COPYRIGHT` - Copyright 2020 MEF Forum
- `LICENSE` - Contains a copy of the Apache 2.0 license
- `README` - This file
- `api` - Definitions of the API are found in this directory
  - `\cantata\order` - Contains the API definitions for inter-carrier service
    ordering capability.
- `doc` - All related standards and Developer Guides.
  - `\cantata-sonata\carrierEthernet` - automatically generated documentation
    for EPL
  - standards - The rest of documents and standards.
  - uml - A collection of UML diagrams generated from all of the API files.
- staticBinding - Contains static bindings of envelope APIs with Product
  Specification payloads. It comes in OpenAPI 3.0.

NOTE: Please note the Readme files in particular directories that provide more
detailed information about corresponding functionalities. All superseded files
can be found in the Git history if needed.

## Precedents

Any developer intending to use the materials in this repository should first
thoroughly read, review, and understand the following materials:

- [MEF 55: Lifecycle Service Orchestration (LSO): Reference Architecture and Framework](doc/standards/MEF%2055%20-%20LSO%20Reference%20Architecture%20and%20Framework.pdf)
  This document is a ratified MEF standard.
- [MEF 55.0.1: Amendment to MEF 55: Operational Threads](doc/standards/MEF%2055.0.1%20-%20Operational%20Threads.pdf)
  This document is a ratified MEF standard.
- [MEF 55.0.2: Amendment to MEF 55: TOSCA Services Templates](doc/standards/MEF%2055.0.2%20-%20TOSCA%20Service%20Templates.pdf)
  This document is a ratified MEF standard.
- [MEF 50.1: MEF Services Lifecycle Process Flows](doc/standards/MEF%2050.1%20-%20MEF%20Services%20Lifecycle%20Process%20Flows.pdf)
  This document is a ratified MEF standard.
- [MEF 57.2: Draft Release 1 Product Order Management Requirements and Use Cases](https://www.mef.net/wp-content/uploads/2020/11/MEF-57.2-Draft-R1.pdf)
  Draft Release 1

## Issues, questions, and Feedback

Issues should be reported with the use of GitHub issues. Questions and feedback
should be asked either at
[Sonata SDK Community](https://github.com/orgs/MEF-GIT/teams/mef-lso-sonata-sdk-community)
or directly to community_manager@mef.net.

**NOTE:** All artifacts included in this repository have line numbers. When referring to specific content in any of these artifacts, please quote the line numbers to which you are referring.

The MEF LSO Sonata SDK is released under the Apache 2.0 license.

## Copyright

© MEF Forum 2020. All Rights Reserved.

## Disclaimer

The information in this publication is freely available for reproduction and use by any recipient and is believed to be accurate as of its publication date. Such information is subject to change without notice and MEF Forum (MEF) is not responsible for any errors. MEF does not assume responsibility to update or correct any information in this publication. No representation or warranty, expressed or implied, is made by MEF concerning the completeness, accuracy, or applicability of any information contained herein and no liability of any kind shall be assumed by MEF as a result of reliance upon such information.

The information contained herein is intended to be used without modification by the recipient or user of this document. MEF is not responsible or liable for any modifications to this document made by any other party.

The receipt or any use of this document or its contents does not in any way create, by implication or otherwise:

(a) any express or implied license or right to or under any patent, copyright, trademark or trade secret rights held or claimed by any MEF member which are or may be associated with the ideas, techniques, concepts or expressions contained herein; nor

(b) any warranty or representation that any MEF member will announce any product(s) and/or service(s) related thereto, or if such announcements are made, that such announced product(s) and/or service(s) embody any or all of the ideas, technologies, or concepts contained herein; nor

(c) any form of relationship between any MEF member and the recipient or user of this document.

Implementation or use of specific MEF standards, specifications, or recommendations will be voluntary, and no Member shall be obliged to implement them by virtue of participation in MEF Forum. MEF is a non-profit international organization to enable the development and worldwide adoption of agile, assured, and orchestrated network services. MEF does not, expressly or otherwise, endorse or promote any specific products or services.
