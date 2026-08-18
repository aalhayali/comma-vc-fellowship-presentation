# Energy Infrastructure VC Thesis — Research Notes

## Core thesis

Energy infrastructure is becoming compute infrastructure. The macro shift is not just “more power demand”; it is that AI data centers, industrial reshoring, electrification, and grid reliability pressure are arriving faster than the physical grid can expand. The venture opportunity is in the operating layer that converts constrained physical infrastructure into usable MW faster: interconnection intelligence, grid-capacity optimization, flexible-load orchestration, data-center power tooling, and transformer/substation bottleneck software.

## Macro facts

- U.S. five-year load growth forecasts rose almost five-fold in two years, from 23 GW to 128 GW.
  - Source: Grid Strategies, “Strategic Industries Surging: Driving US Power Demand,” Dec 2024.
  - URL: https://gridstrategiesllc.com/wp-content/uploads/National-Load-Growth-Report-2024.pdf

- Data centers consumed about 4.4% of total U.S. electricity in 2023 and are expected to consume approximately 6.7% to 12% by 2028. Total data center electricity use rose from 58 TWh in 2014 to 176 TWh in 2023, with DOE/LBNL estimating 325–580 TWh by 2028.
  - Source: DOE, “DOE Releases New Report Evaluating Increase in Electricity Demand from Data Centers,” Dec 2024.
  - URL: https://www.energy.gov/articles/doe-releases-new-report-evaluating-increase-electricity-demand-data-centers

- Globally, data centers, AI, and crypto consumed roughly 460 TWh in 2022 and could exceed 1,000 TWh by 2026.
  - Source: IEA, Electricity 2024.
  - URL: https://www.iea.org/reports/electricity-2024

- Goldman Sachs estimates AI/data-center power demand could increase 160% by 2030 and notes that a ChatGPT query uses nearly 10x the electricity of a Google search on average.
  - Source: Goldman Sachs, “AI is poised to drive 160% increase in data center power demand,” 2024.
  - URL: https://www.goldmansachs.com/insights/articles/AI-poised-to-drive-160-increase-in-power-demand

- U.S. interconnection queues contain nearly 2,600 GW / 2.6 TW of active generation and storage capacity. Solar, storage, and wind are ~95% of active queue capacity. Only ~19% of projects requesting interconnection from 2000–2018 reached commercial operation by the end of 2023.
  - Source: Lawrence Berkeley National Laboratory, “Queued Up: 2024 Edition,” Apr 2024.
  - URL: https://emp.lbl.gov/sites/default/files/2024-04/Queued%20Up%202024%20Edition_1.pdf

## Macro thesis

The old assumption was that electricity demand growth would remain modest and predictable. AI data centers break that assumption because the load is:

1. Large — hundreds of MW to GW-scale clusters.
2. Fast — data centers can be built faster than transmission/generation.
3. Lumpy — concentrated at specific substations/regions.
4. Reliability-sensitive — uptime requirements make firm power valuable.
5. Strategically important — compute is now geopolitical and corporate infrastructure.

This makes “time-to-power” a board-level metric. The bottleneck stack is:

- Load: AI data centers, manufacturing, EVs, heat pumps, industrial electrification.
- Firm power: nuclear, geothermal, gas, storage, demand response, hybrid PPAs.
- Wires/grid: transmission, interconnection, substations, transformers, protection studies.
- Operations: VPPs, DERMS, batteries, C&I load flexibility, EV charging, HVAC.
- Software/AI: siting, queue-risk analytics, forecasting, procurement, asset health, dispatch.

## Micro thesis: where early-stage VC can win

The best early-stage opportunities are not usually pure project developers. They are software or hardware-enabled wedges around slow infrastructure:

### 1. Interconnection intelligence

- Problem: queue risk can kill renewable, storage, and data-center projects.
- Product wedge: site screening, queue-position analytics, cluster-study modeling, upgrade-cost exposure, affected-system tracking, document automation.
- Customers: IPPs, storage developers, data-center developers, utilities, consultants.
- Business model: SaaS + data/API + project-based fees.
- Examples/categories: Paces, Pearl Street Technologies, GridUnity, Transect, Kevala, Enverus.
- Key risk: ISO/utility data quality, long enterprise cycles, engineering-consulting incumbents.

### 2. Flexible interconnection / capacity marketplaces

- Problem: loads and generators wait years for firm interconnection.
- Product wedge: connect faster by agreeing to curtailment, export limits, operating envelopes, telemetry, and dispatch commitments.
- Customers: utilities, large loads, EV charging networks, DER aggregators, data centers.
- Business model: utility SaaS, $/MW managed, transaction fees on flexibility markets.
- Examples/categories: Piclo, Electron, Leap, Camus Energy, Smarter Grid Solutions.
- Key risk: regulatory approval and fragmented utility rules.

### 3. Grid-enhancing technologies

- Problem: new transmission can take many years; existing lines are under-instrumented.
- Product wedge: dynamic line ratings, topology optimization, reconductoring analytics, congestion management, sensor-driven “virtual transmission.”
- Customers: transmission owners, utilities, ISOs/RTOs, large interconnection customers.
- Business model: hardware + SaaS, utility capex plus monitoring subscription, performance/shared-savings models.
- Examples/categories: LineVision, Heimdall Power, Smart Wires, NewGrid, TS Conductor, Prisma Photonics.
- Key risk: utility conservatism, cybersecurity, proving value in planning models.

### 4. DER orchestration / virtual power plants

- Problem: peak capacity and grid flexibility are scarce.
- Product wedge: aggregate batteries, EV chargers, thermostats, HVAC, water heaters, solar inverters, and C&I load into dispatchable capacity.
- Customers: utilities, retail energy providers, OEMs, C&I asset owners.
- Business model: $/kW-year capacity payments, utility program SaaS, market revenue share.
- Examples/categories: EnergyHub, AutoGrid/Schneider, Voltus, OhmConnect, Leap, Sunnova, Tesla Autobidder.
- Key source: DOE Liftoff estimates the U.S. may need 80–160 GW of VPP capacity by 2030.
- URL: https://liftoff.energy.gov/virtual-power-plants/

### 5. Transformer / switchgear / substation bottlenecks

- Problem: long lead times for transformers and high-voltage equipment gate energization.
- Product wedge: procurement marketplaces, lead-time intelligence, design standardization, refurbished equipment QA, substation digital twins, transformer thermal monitoring, spares management.
- Customers: utilities, EPCs, data-center developers, renewables developers, electrical distributors.
- Business model: marketplace take-rate, procurement SaaS, QA/inspection fees, monitoring subscriptions.
- Examples/categories: Amperesand, Heron Power, Gridware, Camlin Energy, Maddox, Sunbelt Solomon.
- Key risk: low-margin distribution dynamics, warranty/liability, certification.

### 6. Data-center power OS

- Problem: AI data-center development is increasingly power-constrained.
- Product wedge: power siting, grid-constraint screening, PPA structuring, behind-the-meter optimization, storage/backup dispatch, flexibility monetization, hourly carbon matching.
- Customers: hyperscalers, colocation providers, data-center developers, utilities, energy developers.
- Business model: SaaS + advisory, energy-management fee, project origination fee, shared savings.
- Examples/categories: Gridmatic, FlexGen, Enchanted Rock, Bloom Energy, Crusoe, Lancium.
- Key risk: concentrated customers and bespoke projects.

## AI in energy infrastructure

AI matters in two ways:

1. AI as demand shock.
   - Data centers are becoming large, urgent, firm-load customers.
   - Hyperscalers are moving upstream into power procurement because annual renewable PPAs are not enough for 24/7 AI load.

2. AI as grid operating layer.
   - Defensible AI is not a generic copilot; it is AI tied to physical assets, proprietary operational data, and measurable actions.
   - Strong use cases: interconnection automation, asset inspection, vegetation/wildfire risk, outage prediction, load forecasting, transformer health, DER dispatch, battery/storage optimization, power market forecasting.

Defensible AI characteristics:

- Controls or optimizes real assets: batteries, flexible loads, DERs, EV chargers, HVAC, backup generation.
- Uses proprietary operational data: SCADA/AMI/GIS, asset histories, imagery, outage records, feeder models, maintenance logs.
- Produces measurable ROI: more MW, lower outages, deferred capex, better dispatch P&L, avoided demand charges.
- Integrates into legacy systems and produces audit trails utilities can defend to regulators.

Weak AI characteristics:

- Generic utility copilots without workflow integration.
- Dashboards that diagnose but do not trigger work orders, dispatch, procurement, or rate-case evidence.
- “Autonomous grid” claims that ignore safety, reliability, and regulatory liability.
- Forecasting tools without differentiated data access or control rights.

## Hyperscaler market signals

- Microsoft + Constellation: 20-year PPA to restart Three Mile Island Unit 1 as the Crane Clean Energy Center; ~835 MW; target restart 2028; estimated $1.6B investment.
  - URL: https://www.microsoft.com/en-us/microsoft-cloud/blog/2024/09/20/microsoft-and-constellation-to-launch-crane-clean-energy-center-restore-jobs-and-carbon-free-power-to-the-grid/

- Amazon/AWS: acquired Talen Cumulus data-center campus near Susquehanna nuclear plant for ~$650M; also announced SMR investments with X-energy/Energy Northwest and Dominion.
  - URL: https://www.talenenergy.com/news-releases/news-release-details/talen-energy-sells-cumulus-data-assets-amazon-web-services
  - URL: https://www.aboutamazon.com/news/sustainability/amazon-nuclear-energy-projects-carbon-free

- Google + Kairos Power: corporate agreement to purchase power from multiple SMRs; initial deployment targeted by 2030, additional deployments through 2035.
  - URL: https://blog.google/outreach-initiatives/sustainability/google-kairos-power-nuclear-energy-agreement/

- Google + Fervo: enhanced geothermal partnership for carbon-free power.
  - URL: https://blog.google/outreach-initiatives/sustainability/google-fervo-geothermal-energy-partnership/

- Meta + Sage Geosystems: agreement for up to 150 MW of geothermal power, targeted later this decade.
  - URL: https://www.meta.com/newsroom/press-releases/2024/08/meta-sage-geosystems-geothermal-energy-agreement/

- OpenAI Stargate: announced up to $500B over four years for U.S. AI infrastructure, with $100B initially deployed.
  - URL: https://openai.com/index/announcing-the-stargate-project/

## Suggested 5-minute talk track

1. 20 sec — Hook: “The next AI bottleneck is not chips; it is usable megawatts.”
2. 45 sec — Macro facts: load growth inflection, data-center demand, interconnection queues.
3. 45 sec — Macro thesis: time-to-power is now strategic infrastructure.
4. 60 sec — Bottleneck stack: load, firm power, wires, operations, software.
5. 90 sec — Micro thesis: interconnection intelligence, flexible interconnection, grid-enhancing tech, VPPs, transformer/substation stack, data-center power OS.
6. 45 sec — AI angle: AI is both demand shock and operating layer; defensibility requires proprietary data + controls + auditability.
7. 45 sec — Closing: “Back the companies that sell time-to-power.”

## Short follow-up note to Lindsey Li

Hi Lindsey — I remembered energy infrastructure was one of the areas you were spending time on, so I’m sending over a short thesis deck I put together for the Comma Capital fellowship.

The punchline: I think the best early-stage opportunities are less “more generation” and more the operating layer that sells time-to-power — interconnection intelligence, grid capacity optimization, flexible-load orchestration, and data-center power tooling. AI is the demand shock, but also part of the tooling if it is tied to proprietary grid data and real operational controls.

Would love your reaction, especially on whether this maps to what you’re seeing from the Bessemer side.

Best,
Abdullah
