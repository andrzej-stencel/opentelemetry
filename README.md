# Elastic OpenTelemetry Distributions

[OpenTelemetry](https://opentelemetry.io/docs/) is a vendor- and tool-neutral observability framework for collecting, processing, and exporting telemetry data.
You have options when using OpenTelemetry to send your telemetry data to Elastic Observability.

- Use the Elastic distribution of the [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) to collect and send logs and host metrics to [Elastic Cloud](https://cloud.elastic.co/).
- Use Elastic distributions of OpenTelemetry Java, .NET, Node.js, and Python to instrument your applications and send logs, traces, and metrics to [Elastic Cloud](https://cloud.elastic.co/).
- Configure a custom or contrib distribution of the OpenTelemetry Collector to collect logs and metrics and send them to Elastic Observability.

This diagram provides a quick overview on how the the different components work together. Refer to the [components](docs/collector-components.md) for a more in-depth look.

![Diagram of the OpenTelemetry flow](docs/images/elastic-otel-overview.png)

## Get started with the Elastic distribution of the OpenTelemetry Collector

These pages detail the components and configuration of the Elastic distribution of the OpenTelemetry collector.

- [Components](docs/collector-components.md): Details on the components used to receive, process, and export telemetry data.
- [Guided onboarding](docs/guided-onboarding.md): Use the guided onboarding in Kibana or a serverless Observability project to send data using the Elastic OpenTelemetry Collector.
- [Manual configuration](docs/manual-configuration.md): Manually configure the Elastic OpenTelemetry Collector to send data to Elastic Observability.
- [Limitations](docs/collector-limitations.md): Current limitations of the Elastic OpenTelemetry Collector.

## Configure Elastic distributions of OpenTelemetry programming languages
<!-- Colleen can fill in these links? -->

## Configure a custom or contrib collector for Elastic

[Configure a custom or contrib collector](docs/configure-custom-collector.md): Configure a [custom](https://opentelemetry.io/docs/collector/custom-collector/) or [contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) distribution to collect logs and metrics and send them to Elastic Observability.