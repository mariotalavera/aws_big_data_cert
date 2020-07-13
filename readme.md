# AWS Big Data Cert Study Guide

## Introduction

This is a documentation project for hte material necessary to know for the AWS Big Data Certification.

## Demo Application

We are building one of these - [Demo App](demo_app_for_class.md)

## Setting Up A Budget

AWS costs money.  Course estimates a $10 cost for running the proposed application in AWS.

Lets setup a budget and an email alert for when we reach 90% of our budget.

[Setting up AWS Budget](https://console.aws.amazon.com/billing/home?region=us-east-1#/budgets)

## AWS Services Used In Study Guide

The AWS Services in use for this cert can be roughly divided into the following categories.

### Collection Category

The collection category encompases the AWS products that deal with collecting data from logs, applications, services, etc.  
Data collection can be roughly divided into the three main scenarios.  Depending in the scenario/requirement, the following AWS services are available.

* Real Time - Immediate actions
  * Kinesis Data Streams (KDS)
  * Simple Queue Service (SQS)
  * Internet Of Things (IoT)

* Neat Real Time - Reactive actions
  * Kinesis Data Firehose (KDF)
  * Database Migration Service (DMS)

* Batch - Historical analysis
  * Snowball
  * Data Pipeline

## Services

* [Amazon Kinesis](amazon_kinesis.md)
* [AWS IoT Core](aws_iot_core.md)
* [AWS Snowball](aws_snowball.md)
* [Amazon SQS](amazon_sqs.md)
* [Amazon DMS](amazon_dms.md)
* [AWS Direct Connect](aws_direct_connect.md)

### Storage Category

### Processing Category

### Analysis Category

### Visualization Category

### Security Category

