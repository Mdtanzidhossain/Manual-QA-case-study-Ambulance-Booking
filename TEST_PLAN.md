# Test Plan — Ambulance Booking

Objectives: Validate booking reliability, SLAs, and error handling.

Scope: Pickup/drop, ambulance types (AC/Non-AC, ICU, Boat/Air if offered), ETA/policy, cancel.

Test Types: Functional, Negative, Edge (no-permission location, out-of-coverage), Basic performance hints, Accessibility quick checks.

Data: Locations inside/outside service area; rapid repeat requests; peak-hour timestamps.

Entry/Exit: Build deployable; mock keys available / ≥95% P1 pass, zero Sev-1.

Risks: Geocode latency; SLA mismatch; surge logic confusion.

> Anonymized, documentation-only portfolio. Full artifacts available under NDA on request.
