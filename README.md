# Qdrant Cloud Grafana Dashboard

This repository contains Grafana dashboards that are designed to visualize the performance and status of Qdrant database clusters running on the Qdrant Cloud Platform, or the Qdrant Private Cloud and Hybrid Cloud control plane components.

## Qdrant Cloud Dashboard

This dashboard visualizes the performance and status of Qdrant database clusters running on the Qdrant Cloud Platform.

It does not work with the metrics that are exposed by the Qdrant open-source container image.

For more information on how to scrape metrics for Qdrant databases in Qdrant Cloud, see https://qdrant.tech/documentation/guides/monitoring/#monitoring-in-qdrant-cloud.

## Qdrant Cloud Operator Dashboard

This dashboard visualizes metrics from the Qdrant operator component running as part of Qdrant Hybrid Cloud or Qdrant Private Cloud.

## Installation

Once you have the metrics available in your monitoring system, you can follow 
https://grafana.com/docs/grafana/latest/dashboards/build-dashboards/import-dashboards/ to import the respective dashboard json file into your Grafana instance.
