<!--
title: 'AWS Python Example'
description: 'This template demonstrates how to deploy a Python function running on AWS Lambda using the traditional Serverless Framework.'
layout: Doc
framework: v3
platform: AWS
language: python
priority: 2
authorLink: 'https://github.com/serverless'
authorName: 'Serverless, inc.'
authorAvatar: 'https://avatars1.githubusercontent.com/u/13742415?s=200&v=4'
-->


# Serverless Framework to create SNS Topic and Topic Policy

This template demonstrates how to deploy SNS topic and add Access policy for S3 bucket to publish messages to SNS using the Serverless Framework. 

## Usage

### Deployment

In order to deploy the example, you need to run the following command:

```
$ serverless deploy
```

After running deploy, you should see output similar to:

```bash
Deploying sns-topic-with-policy to stage dev (us-east-1)

✔ Service deployed to stack sns-topic-stack (103s)


Need a faster logging experience than CloudWatch? Try our Dev Mode in Console: run "serverless dev"
```
