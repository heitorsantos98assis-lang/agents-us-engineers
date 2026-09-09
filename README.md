# 57 Agents for US Engineers

**57 specialized Claude Code subagents for US-licensed Professional Engineers (civil, structural, electrical, mechanical, MEP)** — built by senior practitioners, regulated for US business reality.

Each agent is a single drop-in Markdown file you copy into `.claude/agents/`. Claude Code routes work to the right specialist automatically.

---

## What's inside

| # | Agent | Focus |
|---|---|---|
| 01 | 01-reinforced-concrete-design-aci-318 | Specialist in reinforced concrete design per ACI 318-19/25 (Building Code Requirements for Structural Concrete) and ASCE/SEI 7- |
| 02 | 02-structural-steel-design-aisc-360 | Specialist in structural steel design per AISC 360-22 (Specification for Structural Steel Buildings, 16th ed |
| 03 | 03-wood-design-nds | Specialist in structural wood design per AWC NDS 2024 (National Design Specification for Wood Construction) and AWC SDPWS 2021  |
| 04 | 04-masonry-design-tms-402 | Specialist in structural masonry design per TMS 402-22 (Building Code Requirements for Masonry Structures) and TMS 602-22 (Spec |
| 05 | 05-shallow-foundation-design-spread-footing-mat | Specialist in shallow foundation design — isolated spread footings, continuous wall footings, combined footings, strap footings |
| 06 | 06-deep-foundation-design-piles-drilled-shaft | Specialist in deep foundation design — driven piles (steel pipe per ASTM A252, HP steel per A572 Gr 50, precast prestressed con |
| 07 | 07-retaining-wall-design-tieback-soil-nail | Specialist in earth-retention design — gravity walls, cantilever (concrete + masonry per ACI 318 + TMS 402), MSE (Mechanically  |
| 08 | 08-post-tensioned-concrete-slab-design | Specialist in post-tensioned (PT) concrete slab design — flat plate, flat slab with drops, banded one-way, two-way unbonded sys |
| 09 | 09-structural-condition-assessment-existing-buildings | Specialist in structural condition assessment, forensic evaluation, repair, and rehabilitation of existing buildings — per ASCE |
| 10 | 10-electrical-design-residential-nec | Specialist in residential and light-commercial electrical design per NEC NFPA 70-2023 (and 2026 once state-adopted), with CA-sp |
| 11 | 11-electrical-design-commercial-industrial-medium-voltage | Specialist in commercial + industrial + medium-voltage electrical design per NEC NFPA 70-2023 (Art 215, 220, 230, 240, 250, 408 |
| 12 | 12-lightning-protection-system-nfpa-780 | Specialist in lightning protection system (LPS) design per NFPA 780-2023 (Standard for the Installation of Lightning Protection |
| 13 | 13-utility-service-entrance-interconnection | Specialist in utility service entrance + interconnection design — coordinates new service applications, primary + secondary met |
| 14 | 14-electrical-load-schedule-phase-balancing | Specialist in electrical load schedules + phase balancing + panel scheduling per NEC NFPA 70-2023 Art 220 (Branch + Feeder + Se |
| 15 | 15-solar-pv-grid-interactive-design | Specialist in grid-interactive solar PV + ESS design per IEEE 1547-2018 (DER interconnection), UL 1741 SB (smart inverter Sourc |
| 16 | 16-ev-charging-station-evse-design | Specialist in EV charging station (EVSE) design — residential Level 1/2, commercial Level 2 fleet + public, DC Fast Charge (DCF |
| 17 | 17-structured-cabling-ansi-tia-568 | Specialist in structured cabling system design per ANSI/TIA-568.0-E / 568.1-E / 568.2-E / 568.3-E (Commercial Building Telecomm |
| 18 | 18-residential-plumbing-design-ipc-upc | Specialist in residential + small commercial plumbing design per IPC 2024 (International Plumbing Code, ~25 states) or UPC 2024 |
| 19 | 19-on-site-wastewater-septic-design | Specialist in on-site wastewater treatment system (OWTS) design — septic tank + drainfield (leach field), mound systems, sand f |
| 20 | 20-stormwater-management-design | Specialist in stormwater management design — site drainage, water quality treatment, detention + retention, low-impact developm |
| 21 | 21-greywater-rainwater-harvesting-design | Specialist in non-potable water reuse — greywater (laundry / lavatory / shower), rainwater harvesting (RWH), and stormwater cap |
| 22 | 22-fire-protection-sprinkler-standpipe-design | Specialist in fire protection design — automatic sprinkler systems (NFPA 13 / 13R / 13D), standpipe + hose systems (NFPA 14), f |
| 23 | 23-fuel-gas-piping-design | Specialist in fuel gas piping design — natural gas (NG) + liquefied petroleum (LP / propane) — for residential + commercial + l |
| 24 | 24-pool-spa-design-ispsc | Specialist in swimming pool + spa design per ICC ISPSC 2024 (International Swimming Pool + Spa Code), ANSI/APSP/ICC-5 (Resident |
| 25 | 25-hvac-design-ashrae | Specialist in HVAC design — heating, cooling, ventilation, energy modeling, refrigerant safety, indoor environmental quality —  |
| 26 | 26-mechanical-ventilation-design | Specialist in mechanical ventilation design — outdoor air for IAQ, local exhaust, demand-controlled ventilation (DCV), energy r |
| 27 | 27-commercial-kitchen-ventilation-design | Specialist in commercial kitchen ventilation design — Type I (grease) + Type II (heat/moisture) hoods, exhaust duct, makeup air |
| 28 | 28-industrial-utilities-compressed-air-steam | Specialist in industrial utility systems — compressed air (instrument + plant), steam + condensate, process water (chilled, hot |
| 29 | 29-preliminary-cost-estimate-class-3-2 | Senior cost engineer for AACE Class 5–3 preliminary / order-of-magnitude / schematic-design budgets on US building, civil, and  |
| 30 | 30-detailed-cost-estimate-csi-masterformat-rsmeans | Senior estimator for AACE Class 2 / Class 1 detailed quantity-takeoff and unit-price building / civil construction estimates |
| 31 | 31-overhead-profit-federal-cost-plus | Senior contract pricing engineer / cost accountant for US engineering firm and construction overhead, fee, and federal cost-plu |
| 32 | 32-project-schedule-cpm-ms-project-p6 | Senior project planner / scheduler (PMI-SP, AACE PSP) for CPM (Critical Path Method) project schedules in US engineering and co |
| 33 | 33-s-curve-monthly-progress-billing | Senior project controls engineer for cost-loaded S-curve cash flow forecasting and monthly progress billing on US AEC projects |
| 34 | 34-wbs-work-breakdown-structure | Senior project planner for Work Breakdown Structure decomposition on US AEC and federal engineering programs |
| 35 | 35-last-planner-system-lean-construction | Lean Construction coach for Last Planner System (LPS) on US AEC projects |
| 36 | 36-earned-value-management-pmi-dod | Senior EVMS analyst (PMI-PMP / EVP) for Earned Value Management on US engineering and federal construction programs |
| 37 | 37-topographic-survey-alta-nsps | Senior survey specialist for US topographic, ALTA/NSPS Land Title, and boundary-adjacent topo work coordinating PE / PLS scopes |
| 38 | 38-spt-soil-boring-investigation-astm-d1586 | Senior geotechnical engineer for US soil boring + Standard Penetration Test (SPT) investigations per ASTM D1586 (SPT), ASTM D24 |
| 39 | 39-drone-photogrammetry-uav-mapping | Senior UAV / sUAS mapping specialist for FAA Part 107 operations and photogrammetric / LiDAR deliverables on US engineering and |
| 40 | 40-parcel-mapping-cadastral-survey | Senior PLS coordination engineer for US boundary, cadastral, plat, and subdivision mapping per the dual US cadastre system — PL |
| 41 | 41-earthwork-cut-fill-volume-estimating | Senior civil engineer for US earthwork takeoff — cut/fill volumes, mass haul, balance, swell/shrink, and OSHA-compliant excavat |
| 42 | 42-environmental-permitting-nepa-cwa-state | Senior environmental engineer / permit specialist for US federal + state environmental permitting on engineering and constructi |
| 43 | 43-site-remediation-restoration-plan | Senior environmental engineer for US site remediation, brownfield redevelopment, and ecological restoration |
| 44 | 44-water-rights-permitting | Senior water resources engineer for US water rights acquisition, transfer, and permitting under the dual riparian (East) + prio |
| 45 | 45-construction-demolition-waste-management-plan | Senior sustainability + environmental engineer for US Construction & Demolition (C&D) Waste Management Plans, LEED-aligned dive |
| 46 | 46-environmental-impact-statement-nepa-state | Senior NEPA / state EIS author for US federal action environmental review and state mini-NEPA documents |
| 47 | 47-construction-site-safety-plan-osha-1926 | Senior construction safety professional (CHST / CSP / ASP) for US Site-Specific Safety Plan (SSSP) + Accident Prevention Progra |
| 48 | 48-occupational-safety-health-program-osha | Senior safety / industrial hygiene professional (CSP / CIH / ARM) for US corporate Occupational Safety + Health Management Syst |
| 49 | 49-osha-exposure-assessment-pels-tlvs | Senior Certified Industrial Hygienist (CIH) for US occupational exposure assessment per OSHA 29 C.F.R |
| 50 | 50-fall-protection-electrical-safety-osha | Senior safety engineer (CSP / SP / ASP-BCSP) for US fall protection + electrical safety per OSHA 29 C.F.R |
| 51 | 51-machine-guarding-pressure-vessels-osha-asme | Senior safety + mechanical engineer (CSP / CMSE / PE) for US machine guarding per OSHA 29 C.F.R |
| 52 | 52-confined-space-emergency-response-osha-nfpa | Senior safety + emergency response engineer (CSP / CHMM / CHST) for US Permit-Required Confined Space (PRCS) entry per OSHA 29  |
| 53 | 53-pe-seal-signature-state-board | Senior US Professional Engineer (PE) practice specialist for state-board licensure, PE seal + signature application, Statement  |
| 54 | 54-forensic-engineering-expert-witness | Senior forensic engineer + expert witness (PE / DFE / NSPE / ASCE) for US litigation, insurance, and Construction Defect / Fail |
| 55 | 55-pre-construction-condition-survey-neighbor | Senior structural / civil PE for US pre-construction condition surveys + vibration / crack monitoring on adjacent properties du |
| 56 | 56-engineering-services-agreement-aia-ejcdc | Senior contracts engineer / general counsel-liaison for US Engineering Services Agreements + Architect-Engineer + Subconsultant |
| 57 | 57-ai-engineering-stack-revit-dynamo-autolisp-claude | Senior US digital design engineer / BIM manager for AI-augmented engineering workflows on Autodesk + Bentley stack |

---

## Install one agent

```bash
cd path/to/your/project
mkdir -p .claude/agents
unzip 01-reinforced-concrete-design-aci-318.zip
cp 01-reinforced-concrete-design-aci-318/01-reinforced-concrete-design-aci-318.md .claude/agents/
```

Restart Claude Code or run `/agents`. Done.

## Install all 57

```bash
unzip completo-57-agents-us-engineers.zip
for z in [0-9][0-9]-*.zip; do unzip -o "$z"; done
mkdir -p ~/.claude/agents
find . -mindepth 2 -name '*.md' -not -name 'HOW-TO-INSTALL.md' -exec cp {} ~/.claude/agents/ \;
```

## How agents work

Each `.md` has YAML frontmatter defining when it fires. Claude Code reads the `description` and routes automatically — or invoke explicitly:

```
Use the reinforced-concrete-design-aci-318 subagent to ...
```

Each agent:
- Knows its scope (when to fire, when NOT to fire — delegates back to peers)
- Carries reference tables (codes, regulations, forms, formulas)
- Operates with a deliberate workflow (inputs → core deliverable → checklists)
- Cites authority in Bluebook style where regulatory ground matters
- Produces deliverables in `/tmp/` for review before pushing forward

## Requirements

- [Claude Code](https://docs.claude.com/claude-code) installed and logged in
- `unzip` on your machine

## Versioning

**v1.0** (May 2026). Updates ship as new uploads to this repo.

---

© HL. Built by operators for operators. No fluff.
