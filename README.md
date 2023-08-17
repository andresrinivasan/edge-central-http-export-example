# Edge Central HTTP Export Example

This repo contains ~~all~~ most* of the content from [the IOTech Edge Central HTTP Export Example](https://docs.iotechsys.com/edge-xpert23/app-services/http/export-events-to-http-endpoints.html) and is intended to help as a quickstart guide for a simple app service.

*I replaced the boring echo service with dad jokes.

## Prerequisites

- [IOTech Edge Central Software](https://www.iotechsys.com/products/edge-central/edge-central-installer-download/) Installed
- A valid (or [eval](https://www.iotechsys.com/resources/evaluating-the-software/edge-central-evaluation/)) license
- [docker and docker compose](https://www.docker.com/) daemon and commands (or [equivalent](https://github.com/abiosoft/colima))
- [curl](https://curl.se/) command
- [jq](https://jqlang.github.io/jq/) command

## Divergence

The following was modified from the documented example to help clarify how the app service pipeline works.

- Added [PrintDataToLog](https://docs.iotechsys.com/edge-xpert23/app-services/built-in-functions-overview.html) to show the trigger in the log
- Removed unused writable functions from TOML
- Simplified [trigger.json](trigger.json)
