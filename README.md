# Introduction
A Grafana dashboard template for monitoring kafka on confluent cloud using their api metrics

This is a sample json file to monitoring your kafka running on confluent cloud using the api metrics provided by confluent.

## What is confluent cloud metrics api
The Confluent Cloud Metrics API provides actionable operational metrics about your Confluent Cloud deployment. This is a queryable HTTP API in which the user will POST a query written in JSON and get back a time series of metrics specified by the query.

Comprehensive documentation is available on docs.confluent.io.

Source:
[Cloud Metrics API](https://api.telemetry.confluent.cloud/docs?&_ga=2.261522893.198852656.1651079120-1208583501.1643921169)

## Metrics Reference
This page provides a reference for the metrics and resources available in the Confluent Cloud Metrics API.

A dataset is a logical collection of metrics that can be queried together. A resource represents an entity against which metrics are collected. A metric is a numeric attribute of a resource, measured at a specific point in time, labeled with contextual metadata gathered at the point of instrumentation. There are two types of metrics:

    Gauge - An instantaneous measurement of a value. Gauge metrics are implicitly averaged when aggregating over time.
    Counter - The count of occurrences in a single (one minute) sampling interval (unless otherwise stated in the metric description). Counter metrics are implicitly summed when aggregating over time.

Metrics that are included in the /export endpoint are marked Exportable. All labels are exported unless otherwise indicated.

Source:
[https://api.telemetry.confluent.cloud/docs/descriptors/datasets/cloud](https://api.telemetry.confluent.cloud/docs/descriptors/datasets/cloud)

## Dashboard
![Dashboard Sample](/images/dashboard.png)
By: [https://www.linkedin.com/in/flinox](https://www.linkedin.com/in/flinox)

## We can improve this dashboard...
Please, if you have suggestions to improve monitoring for new metrics, please let me know, let's work together to improve this and share with the community!