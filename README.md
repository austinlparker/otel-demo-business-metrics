# OpenTelemetry Demo - Business Metric Service

This is a small application designed to be used with the [OpenTelemetry
Demo](https://github.com/open-telemetry/opentelemetry-demo).

## Build

- docker build .

## Runtime Expectations

The intent of this application is to be deployed into a Kubernetes cluster
alongside the otel demo app, then instrumented with OpenTelemetry Operator CRDs.