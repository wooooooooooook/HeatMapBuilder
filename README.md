# HeatMapBuilder

Home Assistant add-on for generating heatmaps from sensor values and floor plan maps.

This repository is the source repository for the add-on. Home Assistant users should install it through the HAaddons repository.

## Installation

Add the HAaddons repository to the Home Assistant add-on store:

```text
https://github.com/wooooooooooook/HAaddons
```

## Add-on Deployment

The add-on source is maintained in [`hassio-addon`](hassio-addon/). Pushes to `main` build and publish the Docker image, then sync the add-on metadata to `wooooooooooook/HAaddons/HeatMapBuilder` via GitHub Actions.
