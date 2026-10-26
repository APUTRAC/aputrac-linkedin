# Industry APU fuel consumption: estimate for 2026

Prepared 2026-10-26. This is an estimate built from IATA's 2026 outlook plus an assumed APU share. Verify every input against its primary source before quoting it.

## Inputs (from IATA's June 2026 outlook, as reported by news outlets)

| Input | Value | Primary page to check |
|---|---|---|
| Airline fuel consumption, 2026 | 104 billion gallons (flat on 2025; the December 2025 outlook had 106 billion) | https://www.iata.org/en/iata-repository/pressroom/presentations/media-briefing-industry-outlook-agm-2026/ |
| Fuel bill, 2026 | about $350 billion (2025: $252 billion) | https://www.iata.org/en/pressroom/2026-releases/06-07-middle-east-disruptions-high-fuel-prices-halve-airline-industry-profitability/ |
| Fuel as a share of operating costs | 31.4% (2025: 25.4%) | same press release |
| Jet fuel price | averaging $152 a barrel (2025: $90) | same press release |
| Implied average fuel cost | about $3.37 a gallon ($350B / 104B gal), after hedging | calculated |

No IATA fuel forecast for 2027 was found. IATA's next outlook (usually December) should be the first to cover 2027.

## The APU share of fuel burn (the weakest input)

- IPCC aviation report: about 1% of total fuel for British Airways (older data). https://archive.ipcc.ch/ipccreports/sres/aviation/127.htm
- One academic paper: roughly 2 to 2.5%, citing IATA (not confirmed against IATA's own publications).
- Bottom-up cross-check (our assumptions, to verify): about 40 million commercial flights a year, a fleet-average APU burn of about 50 gallons an hour (narrowbodies 36 to 41 gal/h and widebodies 66 to 115 gal/h per `aputrac-api/apu_reference.json`, weighted).

| Average APU time per flight | Gallons a year | Share of 104 billion |
|---|---|---|
| 30 minutes | about 1.0 billion | about 1.0% |
| 45 minutes | about 1.5 billion | about 1.4% |
| 60 minutes | about 2.0 billion | about 1.9% |

Best estimate of the share: **about 1.5%**, within a plausible range of 1% to 2.5%.

## Estimate

| APU share | APU fuel (gallons) | Fuel cost at $3.37/gal | Fuel (million tonnes) | CO2 (million tonnes) |
|---|---|---|---|---|
| 1.0% (low) | 1.04 billion | $3.5 billion | 3.2 | 10.0 |
| **1.5% (best)** | **1.56 billion** | **$5.3 billion** | **4.7** | **15.0** |
| 2.0% | 2.08 billion | $7.0 billion | 6.3 | 20.0 |
| 2.5% (high) | 2.60 billion | $8.8 billion | 7.9 | 25.0 |

Conversions: 3.04 kg of fuel per US gallon; 3.16 kg of CO2 per kg of fuel (same as the FE Score tool).

## What it implies for APUTRAC's claims

- "$700M+ wasted a year" equals about 13% of APU fuel at the best estimate (about 20% at the low case, about 8% at the high case). A possible derivation for the website claim: confirm how the claim was actually derived before using this.
- The website's 20% APU reduction example would be about $1.05 billion a year industry-wide at the best estimate.

## How to cite it

Say "roughly" and show the sum: 104 billion gallons x about 1.5% = about 1.56 billion gallons, at about $3.37 a gallon (IATA's $350B / 104B gal) = about $5.3 billion. Call the 1.5% "my estimate" and mention the 1 to 2.5% range.

## To verify before posting

- [ ] 104 billion gallons, $350 billion, 31.4%, $152 a barrel against IATA's pages above (and check for any newer IATA update)
- [ ] The APU share: find a better source, or say it is an estimate
- [ ] Flights per year and average APU minutes per flight (ideally real APU-hour data)
- [ ] How the website's $700M+ was derived
