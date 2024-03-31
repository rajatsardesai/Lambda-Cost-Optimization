# Lambda Cost-Optimization

## Overview
This project aims to optimize AWS Lambda costs by automating the deletion of stale snapshots that are not attached to any volume or whose volume has already been deleted. It utilizes Boto3 with Python3 and CloudWatch to execute a Lambda function as a cron job.

## Prerequisites
🛠️ Before proceeding with the deployment, ensure the following prerequisites are met:

- **Create Test Instance**: Set up an instance to test Lambda function.

- **Create Snapshot**: Create a snapshot of volume attached to the created test instance.

## Deployment Steps
Follow these steps to deploy and test the Lambda function:

- **Create Lambda Function**: Create a Lambda function in the AWS Management Console or using AWS CLI.

- **Insert Code**: Insert the code provided in the code section of this repository into the Lambda function.

## Contribution Opportunity
Contributions to this project are welcome. If you have expertise in AWS Lambda, Python programming, or cost optimization strategies, your contributions can enhance the effectiveness and efficiency of this solution.

## Support
For any queries, issues, or feedback, please feel free to open an issue in the repository. Your feedback is valuable for improving this project.

Happy Cost-Optimizing! 🚀💰