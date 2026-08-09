# Kisumu Flood Risk Dashboard

An interactive tool showing real, sourced flood exposure data for all 35 wards in Kisumu County, Kenya.

## What it does
For each ward, this dashboard shows:
- Total population
- Building count
- Flood hazard area (% of ward at risk, 50-year return period)
- Estimated population and households at risk
- Estimated financial exposure (based on standard humanitarian cost estimates)

An interactive map visualizes flood risk across all wards.

## Data sources
- **Population**: WorldPop 2020 constrained population estimates (data.worldpop.org)
- **Ward boundaries**: HDX / American Red Cross, "Administrative Wards in Kenya 1450"
- **Buildings**: OpenStreetMap (via OSMnx)
- **Flood hazard**: JRC (EU Joint Research Centre) Global River Flood Hazard Maps, 50-year return period

## Notes
- Building data is complete for 30 of 35 wards; the remaining 5 are marked as pending due to data source limitations, not estimated.
- Financial exposure uses a standard humanitarian planning assumption of $10/person/day over a 14-day disruption window — this is a stated estimate, not an audited figure.

## Author
Teresia Kinuthia, Maseno University, School of Planning — Disaster Management with IT
