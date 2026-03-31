# Tribal Coding Group - 2026

Title: **R + ArcGIS: Full Stack Spatial**

This repository contains the code examples that were shown during the workshop.

```
.
├── slides.pdf        // slides!
├── backend-examples  // portal items + geocoding
├── example-apps      // calcite-based shiny apps
└── update-dashboard  // updating ArcGIS dashboard with {arcgis}
```

## Agenda

- "Full-stack" development in R
- Location services with {arcgis}
- R & ArcGIS Dashboards
- App development with {calcite} and {shiny}
- Deployment with [ricochet](https://docs.ricochet.rs/)


## LLM Files

Use these files to aid you in your use and dvelopment using the R-ArcGIS Bridge Packages

- `{arcgislayers}`: https://developers.arcgis.com/r-bridge/llms.txt
- `{arcgisutils}`: https://developers.arcgis.com/r-bridge/llms.txt
- `{arcgisgeocode}`: https://developers.arcgis.com/r-bridge /arcgisgeocode/llms.txt
- `{calcite}`: https://developers.arcgis.com/r-bridge/calcite/llms.txt


## Deploying using ricochet.rs

To deploy your shiny app using ricochet, follow the [quickstart](https://docs.ricochet.rs/v0-4/user/quickstart/index.html) to install the ricochet cli.

- Set your working directory to `example-apps`
- Log in to `try.ricochet.rs` in the UI
- From your terminal run `ricochet login -S https://try.ricochet.rs`
- Deploy with `ricochet deploy -S https://try.ricochet.rs`
- Open the deployment log to watch packages install!
- View the app!