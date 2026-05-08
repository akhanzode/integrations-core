# Datadog DogStatsD

## Overview

This integration surfaces the [client-side telemetry][2] emitted by Datadog's official [DogStatsD][1] client libraries. The metrics are produced by the clients themselves, covering the full lifecycle of metric submission: how many metrics, events, and service checks were sent to the client by the application, how many payloads and bytes were successfully delivered to the Agent, and how many were dropped — whether due to a full sender queue or a writer error. When client-side aggregation is enabled, aggregation context counts are also reported.

## Setup

### Installation

Please see the documentation for [DogStatsD][1].

## Data Collected

### Metrics

See [metadata.csv][3] for a list of metrics provided by this check.

### Events

The Datadog DogStatsD integration does not include any events.

### Service Checks

See [service_checks.json][4] for a list of service checks provided by this integration.

## Troubleshooting

Need help? Contact [Datadog support][5].

[1]: https://docs.datadoghq.com/developers/dogstatsd/
[2]: https://docs.datadoghq.com/extend/dogstatsd/high_throughput/#client-side-telemetry
[3]: https://github.com/DataDog/integrations-core/blob/master/datadog_dogstatsd/metadata.csv
[4]: https://github.com/DataDog/integrations-core/blob/master/datadog_dogstatsd/assets/service_checks.json
[5]: https://docs.datadoghq.com/help/
