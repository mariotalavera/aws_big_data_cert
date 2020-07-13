# Demo App for Class

Case study, about

## Requirements

### Requirement 1 - Order History App

```mermaid
graph LR
a(Server logs) --> b(Amazon Kinesis<br> Data Stream) --> c(AWS<br> Lambda) --> d(Amazon<br> DynamoDB) --> e(Client App)
```

### Requirement 2 - Product Recomendations

```mermaid
graph LR
a(Server Logs) --> b(Amazon Kinesis<br> Data Firehose) --> c(Amazon S3) --> d(Amazon EMR)
```

### Requirement 3 - Predicting Order Quantities

```mermaid
graph LR
a(Server Logs) --> b(Amazon Kinesis<br> Data Firehose) --> c(Amazon S3) --> d(Amazon<br> Machine<br> Learning)
```

### Requirement 4 - Transaction Rate Alarm

```mermaid
graph LR
a(Server Logs) --> b(Amazon Kinesis<br> Data Streams) --> c(Amazon Kinesis<br> Data Analytics) --> d(Amazon Kinesis<br> Data Streams) --> e(AWS<br> Lambda) --> f(Amazon<br> SMS)
```

### Requirement 5 - Near Real Time Log Analysis

```mermaid
graph LR
a(Server Logs) --> b(Amazon Kinesis<br> Data Firehose) --> c(Amazon <br>Elasticsearch<br> Sevice)
```

### Requirement 6 - Data Warehousing & Visualization

```mermaid
graph LR
a(Server Logs) --> b(Amazon Kinesis<br> Firehose) --> c(Amazon S3)

c --> d(AWS Glue) --> e(Amazon<br> Ahena)
c --> f(Amazon<br> Redshift) --> g(Amazon<br> Quicksight)
```

### Putting It All Together

```mermaid
graph LR
a(Server Logs)

a --> b(Amazon Kinesis<br> Data Firehose)
a --> c(Amazon Kinesis<br> Data Stream)

b --> b2(Amazon S3)
b --> b1(Amazon<br> ElasticSearh<br> Service)

b2 --> b3(Amazon<br> Machine<br> Learning)
b2 --> b4(AWS Glue) --> b5(Amazon<br> Athena)
b2 --> b6(Amazon EMR)
b2 --> b7(Amazon Redshift) --> b8(Amazon<br> Quicksight)

c --> d(AWS<br> Lambda) --> f(Amazin<br> DynamoDB) --> g(Client App)
c --> e(Amazon Kinesis<br> Data Analytics) --> h(Amazon Kinesis<br> Data Streams) --> i(AWS<br> Lambda) --> j(Amazon SNS)
```
