# training-tweaks README

This is a very simple readme that sets a few user settings at startup which we can't preset, but would like to alter the defaults without recompiling the server.

## Features

This will set the following user settings at startup:

```json
{
  "update.mode": "none",
  "telemetry.telemetryLevel": "off"
  "extensions.autoCheckUpdates": false,
  "extensions.autoUpdate": false
}
```

## Requirements

There are no special requirements for this extension.

## Known Issues

Setting `update.mode` to `none` officially requires a restart of Visual Studio Code and therefore may not really achieve much initially.

## Release Notes

### 0.0.1

Initial release of training-tweaks
