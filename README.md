# Docker compose file containing useful log sinks for local development.

> [!NOTE]
> This is for **local** development only. There is no authentication or security setup in the compose file. 
> If you want any of that, you'll need to add it yourself.

## Usage

```shell
docker compose up -d
```

Add `OTEL_EXPORTER_OTLP_ENDPOINT=http://localhost:4317` environment variable to your application.

# Tools available

## OpenTelemetry Collector

[OpenTelemetry Collector](https://opentelemetry.io/docs/collector/) is a tool for collecting logs, metrics and traces.

## Seq

[Seq](https://datalust.co/seq/) search, analysis, and alerting server
built for structured logs and traces.

## Aspire Dashboard

[Aspire Dashboard](https://learn.microsoft.com/en-us/dotnet/aspire/fundamentals/dashboard/standalone?tabs=bash) provides
a great UI for viewing telemetry.

