# Travel Booking Metrics Dashboard

This repository contains the metrics dashboard for the Travel Booking microfrontend architecture, tracking build and deployment performance.

## Installation

```bash
npm install
```

## Development

```bash
npm start
```

## Build

```bash
npm run build
```

## Features

- Build time metrics visualization
- Build success rate tracking
- Deployment success monitoring
- Performance trends analysis
- All microfrontends status overview

## Architecture

This is part of a microfrontend architecture using:
- React as the framework
- Chart.js for visualizations
- GitHub API for metrics collection

## CI/CD

This repository uses GitHub Actions for CI/CD pipeline, which will:
- Build and test the code on every PR and push to main
- Collect build metrics
- Deploy to GitHub Pages on push to main

## Metrics Collection

The dashboard collects metrics from all other repositories in the Travel Booking ecosystem:
- `travel-booking-shared-lib`
- `travel-booking-root-config`
- `travel-booking-auth`
- `travel-booking-tours`
- `travel-booking-admin`
- `travel-booking-client`