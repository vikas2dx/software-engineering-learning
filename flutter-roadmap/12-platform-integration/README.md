# Platform Integration

Use plugins for common platform capabilities and platform channels when a required native API has no suitable plugin.

## Learn
- Plugin APIs, platform implementations, and package compatibility.
- Method channels, event channels, codecs, and asynchronous error mapping.
- Android and iOS permissions, lifecycle, deep links, and native build configuration.
- Platform-specific testing and graceful behavior when a capability is unavailable.
- Avoid blocking the platform main thread with expensive work.

## Practice
Integrate one native capability behind a Dart interface. Test permission denial, unsupported platforms, and platform-side errors.

## Ready when
Platform details stay behind a clear boundary and failure modes are handled on both sides of the channel.