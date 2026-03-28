# assets

A repository for hosting and distributing static assets.

## Repository Structure

The following directory structure is maintained for organized asset management:

* **images/**: Contains all image files, subdivided by use case (e.g., charts, screenshots).
* **data/**: Publicly accessible lightweight configuration or sample datasets.
* **docs/**: Documentation, whitepapers, or PDF resources.
* **scripts/**: Automation tools for processing or uploading assets.

## Accessing Assets

To ensure reliable and fast access from different regions, it is recommended to use the jsDelivr CDN.

### URL Pattern
The standard pattern for accessing files via CDN is:
`https://cdn.jsdelivr.net/gh/[username]/assets@[branch]/[path/to/file]`

### Example
To access an image located at `images/charts/price-action-analysis.png` on the `main` branch:
`https://cdn.jsdelivr.net/gh/[username]/assets@main/images/charts/price-action-analysis.png`

## Usage Guidelines

1.  **Naming Convention**: Use lowercase alphanumeric characters and hyphens for filenames (e.g., `btc-analysis-2026.png`). Avoid spaces or special characters.
2.  **Privacy**: This is a public repository. Do not upload sensitive information, API keys, or private trading configurations.
3.  **Organization**: Place files in their respective directories. For high-frequency uploads like screenshots, consider using YYYY-MM subdirectories.

## License

This repository is used for static asset hosting. Distributed content may be subject to individual licensing terms specified within the respective directories.
