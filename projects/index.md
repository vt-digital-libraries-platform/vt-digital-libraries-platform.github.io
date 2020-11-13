---
layout: single
classes: wide
author_profile: true
---
## Project overview

![VTDLP overview](/assets/images/VTDLP_overview.png "VTDLP overview")

## Services
* Access service
  * [IAWA](https://iawa.lib.vt.edu/)
* Derivative service
  * IIIF tile & manifest: [aws-batch-iiif-generator](https://github.com/vt-digital-libraries-platform/aws-batch-iiif-generator)
* Resolution service: [DLP Resolution Service](https://github.com/vt-digital-libraries-platform/resolution-service)
* ID Minting service: [DLP ID Minting Service](https://github.com/vt-digital-libraries-platform/mint)
* Fixity services: [DLP Fixity Service](https://github.com/vt-digital-libraries-platform/FixityService)
* Ingestion services: [DLP metadata ingestion](https://github.com/vt-digital-libraries-platform/S3toDDB)

|         | Count           | 
| ------------- |:-------------:|
| Lambda functions  | 4 |
| Microservices  |    3   |
| Python package |  1   |
| Batch program  |  2  |
| Docker image | 1 |

* Lambda functions
	* [S3toDDB](https://github.com/vt-digital-libraries-platform/S3toDDB)
	* [dlp-access-lambdas](https://github.com/vt-digital-libraries-platform/dlp-access-lambdas)
    * [DLP Lambda layers](https://github.com/vt-digital-libraries-platform/lambda_layers)
	* [DDBtoDDB](https://github.com/vt-digital-libraries-platform/DDBtoDDB)
* Microservices
	* [DLP Resolution Service](https://github.com/vt-digital-libraries-platform/resolution-service)
	* [ID Minting Service](https://github.com/vt-digital-libraries-platform/mint)
	* [aws-batch-iiif-generator](https://github.com/vt-digital-libraries-platform/aws-batch-iiif-generator)
	* [Fixity Service](https://github.com/vt-digital-libraries-platform/FixityService)
* Python package
	* [NOID-mint](https://github.com/vt-digital-libraries-platform/NOID-mint)
* Batch program
	* [AWS Batch Task JSON Generator](https://github.com/VTUL/iiif_s3_tools/tree/master/Batch_task_json_generator)
	* [Index CSV Generator](https://github.com/VTUL/iiif_s3_tools/tree/master/index_csv_generator)
* Docker image
    * [IIIF_S3 docker](https://github.com/vt-digital-libraries-platform/iiif_s3_docker)
