# Inter-Prime Exchange Contract Conformance Template

#### Meta-Instructions Template (Populated)

* Inter-Prime\_Exchange\_Contract\_name: IPEC-Mycelial-Bioregion-A
* Primes: \[Mycelial\_Prime, Bioregion\_A\_Prime]
* SetPoint\_URIs: \[URI for Mycelial Prime SetPoint, URI for Bioregion\_A Prime SetPoint]
* Mode: {Inter-Prime\_Exchange\_Contract\_Transport}
* Message\_Types: {claims, obligations, telemetry, attestations}
* Units: {multi-capital\_vector}
* FX\_policy: {bilateral}; bounds: +/- 5% deviation from 7-day moving average
* Issuance/Limits: {no\_cross-issuance}; rate-limits: 1000 events/day per Prime
* Evidence\_Bindings:
  * Emergence-Echo: {purpose\_map, formal\_map, SetPoint\_refs}
  * Loop-Closure: {FunctionSpec\_ref, FlowTelemetry\_fields, time\_bounds}
  * Trust/Surplus: {boundary\_checks, non-extraction\_attestations}
* Conformance\_Checklist: {identity\_map, schema\_map, validation\_rules, audit\_log, denial\_log}
* Version\_Pins: {Mycelial\_Prime\_rule\_v1.2, Bioregion\_A\_Prime\_rule\_v1.1}; Expiry: 2026-12-31
* Data\_Minimization: {fields allowed; PII handling per GDPR-equivalent protocol}
* Adversarial\_Reviews: cadence {red | yellow | green}: green: 90 days; yellow: 30 days; red: 7 days; steward: \[Cross-Prime Audit Role]
* Kill\_Switch: steward: \[Emergency Governance Role]; triggers: >10% gate failure rate in 24h, unresolved integrity flag from steward
* Supremacy/Exit: {priority\_rule: Bioregion\_A rules apply in case of conflict on local resources, exit\_conditions: 30-day notice with obligation clearing, unwind\_procedure: per Inter-Prime Exchange Contract unwind spec v1.0}
