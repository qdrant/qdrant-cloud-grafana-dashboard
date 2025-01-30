# Qdrant Cloud Grafana Dashboard

This Grafana dashboard is designed to visualize the performance and status of Qdrant database clusters running on the Qdrant Cloud Platform.

It does not work with the metrics that are exposed by the Qdrant open-source container image.

For more information on how to scrape metrics for Qdrant databases in Qdrant Cloud, see https://qdrant.tech/documentation/guides/monitoring/#monitoring-in-qdrant-cloud.

## Installation

Once you have the metrics available in your monitoring system, you can follow 
https://grafana.com/docs/grafana/latest/dashboards/build-dashboards/import-dashboards/ to import the `qdrant-cloud-dashboard.json` file into your Grafana instance.
