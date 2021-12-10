---
layout: single
classes: wide
permalink: /project/
title: "Project"
sidebar:
  - title: "Resources"
  - text: "[**Demo**](https://vtdlp-demo.cloud.lib.vt.edu/)<br>
  [**Docs**](https://github.com/VTUL/dlp-access/wiki)<br>
  [**Code**](https://github.com/VTUL/dlp-access)<br>
  [**Contribute**](https://github.com/VTUL/dlp-access/blob/dev/CONTRIBUTING.md)<br>"
  - title: "Contact"
  - text: "Digital Library Development <br>
            Virginia Tech University Libraries  <br>
            560 Drillfield Drive <br> 
            Blacksburg, VA 24061 <br>  
            [**digital-libraries@vt.edu**](mailto:digital-libraries@vt.edu)"
---
## VTDLP Overview

![VTDLP overview](/assets/images/VTDLP_overview.png "VTDLP overview")

## VTDLP Core Services

| Name        | Description           | GitHub|
| ------------- | ------------- |:-------------:|
| Access Websites  | A Multi-Tenant Serverless Website built with GraphQL, React, AWS Amplify, AWS AppSync, DynamoDB, and ElasticSearch. | [dlp-access](https://github.com/VTUL/dlp-access) |
| Derivative service | A Cloud-based image process service to generate access derivatives using IIIF framework | [aws-batch-iiif-generator](https://github.com/vt-digital-libraries-platform/aws-batch-iiif-generator) |
| Fixity service | Serverless fixity for digital preservation compliance | [FixityService](https://github.com/vt-digital-libraries-platform/FixityService)|
| ID Minting Service   | Accept requests for new Nice Opaque IDentifier(NOID), mint them, verify they're unique, return them to requester | [mint](https://github.com/vt-digital-libraries-platform/mint)
| Metadata CSV file ingestion service| Metadata ingesetion for the VTDLP Access Websites.  | [S3toDDB](https://github.com/vt-digital-libraries-platform/S3toDDB) |
| Resolution Service |  Resolve persistent identifiers   | [resolution-service](https://github.com/vt-digital-libraries-platform/resolution-service) |
| File Deposit Service  |  GUI tools for ingesting and validating new and changed files for access and/or preservation | |
| Metadata Deposit Service | GUI tools for ingesting and validating new and changed metadata for access and/or preservation | |

### VTDLP miscellaneous libraries, tools, etc
* [AWS Batch Task JSON Generator](https://github.com/VTUL/iiif_s3_tools/tree/master/Batch_task_json_generator)
* [DLP Lambda layers](https://github.com/vt-digital-libraries-platform/lambda_layers)
* [DDBtoDDB](https://github.com/vt-digital-libraries-platform/DDBtoDDB)
* [IIIF_S3 docker](https://github.com/vt-digital-libraries-platform/iiif_s3_docker)
* [Index CSV Generator](https://github.com/VTUL/iiif_s3_tools/tree/master/index_csv_generator)
* [NOID-mint](https://github.com/vt-digital-libraries-platform/NOID-mint)
