# Changelog

Please update changelog as part of any significant pull request. Place short
description of your change into "Unreleased" section. As part of release
process content of "Unreleased" section content will generate release notes for
the release.

## Unreleased

- Remove SpanId from Sampler input.

## v0.3.0 (02-21-2020)

- [OTEP-0059](https://github.com/open-telemetry/oteps/blob/master/text/trace/0059-otlp-trace-data-format.md) Add OTLP Trace Data Format specification.
- [OTEP-0066](https://github.com/open-telemetry/oteps/blob/master/text/0066-separate-context-propagation.md) Separate Layer for Context Propagation.
- [OTEP-0070](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0070-metric-bound-instrument.md) Rename metric instrument "Handles" to "Bound Instruments".
- [OTEP-0072](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0072-metric-observer.md) Metric Observer instrument specification (refinement).
- [OTEP-0080](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0080-remove-metric-gauge.md) Remove the Metric Gauge instrument, recommend use of other instruments.
- Update 0003-measure-metric-type to match current Specification.
- Update 0009-metric-handles to match current Specification.
- Clarify named tracers and meters.
- Remove SamplingHint from the Sampling OTEP (OTEP-0006).
- Remove component attribute.
- Allow non-string Resource label values.
- Allow array values for attributes.
- Add service version to Resource attributes.
- Add general, general identity, network and VM image attribute conventions.
- Add a section on transformation to Zipkin Spans.
- Add a section on SDK default configuration.
- Enhance semantic conventions for HTTP/RPC.
- Provide guidelines for low-cardinality span names.
- SDK Tracer: Replace TracerFactory with TracerProvider.
- Update Resource to be in the SDK.

## v0.2.0 (10-22-2019)

- [OTEP-0001](https://github.com/open-telemetry/oteps/blob/master/text/0001-telemetry-without-manual-instrumentation.md) Added Auto-Instrumentation.
- [OTEP-0002](https://github.com/open-telemetry/oteps/blob/master/text/trace/0002-remove-spandata.md): Removed SpanData interface in favor of Span Start and End options.
- [OTEP-0003](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0003-measure-metric-type.md) Consolidatesd pre-aggregated and raw metrics APIs.
- [OTEP-0008](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0008-metric-observer.md) Added Metrics Observers API.
- [OTEP-0009](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0009-metric-handles.md) Added Metrics Handle API.
- [OTEP-0010](https://github.com/open-telemetry/oteps/blob/master/text/metrics/0010-cumulative-to-counter.md) Rename "Cumulative" to "Counter" in the Metrics API.
- [OTEP-006](https://github.com/open-telemetry/oteps/blob/master/text/trace/0006-sampling.md) Moved sampling from the API tp the SDK.
- [OTEP-0007](https://github.com/open-telemetry/oteps/blob/master/text/0007-no-out-of-band-reporting.md) Moved support for out-of-band telemetry from the API to the SDK.
- [OTEP-0016](https://github.com/open-telemetry/oteps/blob/master/text/0016-named-tracers.md) Added named providers for Tracers and Meters.
- Added design goals and requirements for a telemetry data exchange protocol.
- Added a Span Processor interface for intercepting span start and end invocations.
- Added a Span Exporter interface for processing batches of spans.
- Replaced DistributedContext.GetIterator with GetEntries.
- Added clarifications and adjustments to improve cross-language applicability.
- Added a specification for SDK configuration.

## v0.1.0 (06-21-2019)

- Added API proposal for the converged OpenTracing/OpenCensus project is complete.
