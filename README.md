# data.gov.mt (data-gov-mt)

data.gov.mt (Open Data Malta) is Malta's national government open-data portal, built by **MITA** as a bespoke "Shared Data Governance" platform (JS SPA at portal.data.gov.mt / open.data.gov.mt). It is **not** CKAN.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/data-gov-mt/refs/heads/main/apis.yml)

## Type
- **kind:** government  ·  **software:** custom (MITA platform, DCAT-AP)

## API
- **Open Data Malta Portal** — `https://portal.data.gov.mt/`. DCAT-AP-compliant, harvested into data.europa.eu (~230+ datasets).
- **MSDI geoportal** — `https://msdi.data.gov.mt/` exposes standard OGC geospatial services (GeoNetwork CSW, GeoServer WMS/WFS, ArcGIS), distinct from the open-data catalog.
- **Note:** no public, documented JSON/REST catalog API was located; the SPA calls an undocumented internal backend, and all hosts sit behind a Cloudflare anti-bot challenge (HTTP 403 to non-browser clients). A machine-readable surface would need to come from the DCAT-AP feed or browser-captured XHR calls.

## Timestamps
- **Created:** 2026-06-23
- **Modified:** 2026-06-23

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
