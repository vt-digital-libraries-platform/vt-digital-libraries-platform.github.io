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
* Resolution service: [Resolution Service](https://github.com/vt-digital-libraries-platform/resolution-service)


|         | Count           | 
| ------------- |:-------------:|
| Lambda functions  | 4 |
| Microservices  |    2   |
| Python package |  1   |
| Batch program  |  2  |
| Docker image | 1 |

* Lambda functions
	* [S3toDDB](https://github.com/vt-digital-libraries-platform/S3toDDB)
	* [DynamoDB Stream processing](https://github.com/vt-digital-libraries-platform/ddbstreamprocessing)
    * [DLP Lambda layers](https://github.com/vt-digital-libraries-platform/lambda_layers)
	* [DDBtoDDB](https://github.com/vt-digital-libraries-platform/DDBtoDDB)
* Microservices
	* [DLP Resolution Service](https://github.com/vt-digital-libraries-platform/resolution-service)
	* [aws-batch-iiif-generator](https://github.com/vt-digital-libraries-platform/aws-batch-iiif-generator)
* Python package
	* [NOID-mint](https://github.com/vt-digital-libraries-platform/NOID-mint)
* Batch program
	* [AWS Batch Task JSON Generator](https://github.com/VTUL/iiif_s3_tools/tree/master/Batch_task_json_generator)
	* [Index CSV Generator](https://github.com/VTUL/iiif_s3_tools/tree/master/index_csv_generator)
* Docker image
    * [IIIF_S3 docker](https://github.com/vt-digital-libraries-platform/iiif_s3_docker)
<!-- * SNS / SQS / DLQs -->
<!-- * System Manager params  -->
<!-- * API Gateway endpoints -->
<!-- * DynamoDB tables -->
<!--	* IAWA: Collection, Archive -->
<!--	* DLP Resolution Service: resolution --> 
<!-- * S3 Buckets -->
<!-- * Elastic Search -->
<!--	* VTDLP ES -->