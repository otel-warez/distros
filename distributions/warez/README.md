# OpenTelemetry Collector Warez Distro

This distribution contains all the components from both the [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) repository and the [OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib) repository. This distribution includes open source and vendor supported components.

It also contains all the community components hosted outside contrib. Just ask to add your component.

## Recommendation

This distribution is everything and the kitchen sink, and we are ready to sprinkle more on it. You are welcome to try it out, send feedback in issues, and push the boundaries by customizing it with your own fork.

Building a [custom collector](https://opentelemetry.io/docs/collector/custom-collector/) can be achieved using the [OpenTelemetry Collector Builder](https://github.com/open-telemetry/opentelemetry-collector/tree/main/cmd/builder).

## Components

The full list of components is available in the [manifest](manifest.yaml)

### Rules for Component Inclusion

- Include all components that are ready to be played with.
- All components and dependencies must be compatible with the Apache 2.0 Software License.
- Components that fail to compile with the latest stable or latest build of the collector APIs will be removed.