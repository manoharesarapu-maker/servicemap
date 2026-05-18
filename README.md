# Council Service × Technology Opportunity Map v6

This package refines the uploaded v5 HTML into an executive-ready v6 prototype.

## What changed
- Executive summary is now the default view.
- Introductory guide explains purpose, audience and navigation.
- Plain-English labels replace L1/L2 jargon: Service Categories and Specific Services.
- Maturity and horizon filters added: Proven, Emerging, Experimental; Now, Near-term, Future.
- Top Opportunities mode added with rationale and impact/feasibility indicators.
- Governance and risk layer added for technologies and sensitive services.
- Vendor-specific Sen* product lens moved into a separate Vendor Solution Example modal.
- Readability improved with larger base type, stronger contrast and a light/print mode.
- Print/PDF export supported via the browser print dialogue.
- Data decoupled into data/council-service-map-data.json.

## Hosting notes
- Open through a web server or SharePoint-hosted location so the browser can load the external JSON file.
- Place a locally hosted D3 v7 file at vendor/d3.v7.min.js for government network resilience. The current HTML includes a CDN fallback for convenience during testing.
- For a fully offline build, add D3 locally and remove the CDN fallback block from index.html.

## Validation checklist
- Executive understands the purpose within 30 seconds.
- Executive can identify a priority opportunity within 2 minutes.
- User can move between Summary, Explore and Card Grid without losing Home navigation.
- Sensitive services display governance flags.
- Product lens is clearly vendor-specific and separate from the generic technology patterns.
