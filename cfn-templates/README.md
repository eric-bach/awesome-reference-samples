# Description

This repo contains a reference of useful CloudFormation templates for common use cases

## DynamoDB

- [DynamoDb.yaml](src/DynamoDb.yaml): creates a simple DynamoDB table with some GSIs and LSI

## EventBridge

- [EventBridge-Lambda.yaml](src/EventBridge-Lambda.yaml): creates a custom EventBridge rule to invoke a Lambda function

## S3

- [S3-Assume-Role.yaml](src/S3-Assume-Role.yaml) and [S3-Assume-Role.cs](src/S3-Assume-Role.cs): allows an external application to assume a role that can read a S3 bucket

## SNS

- [SNS-invoke-SQS.yaml](src/SNS-invoke-SQS.yaml): allows a SQS queue to subscribe to a SNS topic, useful for pub-sub fan-out
