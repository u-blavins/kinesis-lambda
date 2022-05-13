# Kinesis Lambda Consumer

This repo will be store all the relevant infrastructure as code and source code required to consume data from Kinesis, 
through AWS Lambda.

## Kinesis Background

The Kinesis service from AWS makes it easy to collect, process, and analyze real-time streaming data, so you can get 
timely insights and react quickly to new information. Kinesis will ingest real time data of different formats, enabling
users to process and analyse data as it arrives.

## Overview

This project will use Kinesis Data Stream to capture some data from a producer, and should hopefully set  up AWS Lambda
to consume the real time data that is being ingested into Kinesis.

![Kinesis Data Stream Overview](assets/kinesis-data-stream.png)