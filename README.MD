# jmx_prometheus_sample_app

App to test AWS CloudWatch Container Insights

Built using these instructions: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/ContainerInsights-Prometheus-Sample-Workloads-javajmx.html

## Build locally

```
docker build -t jmx_prometheus_sample_app .
```

## Test

```
docker run jmx_prometheus_sample_app
```

Access app:  http://localhost:8080/sample/

Access metrics: http://localhost:9404/metrics