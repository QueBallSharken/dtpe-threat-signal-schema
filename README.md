# dtpe-threat-signal-schema

Open, privacy-aware schemas for representing abuse and threat signals (phishing, scams, spam, impersonation, bot activity).

## What this is
A small set of JSON/TypeScript schemas and conventions for emitting threat signals in a consistent format.

## What this is NOT
This project does **not** include scoring algorithms, detection logic, persona weighting, ranking, or any proprietary trust engine implementations.

## Contents
- `schema/ThreatSignal.schema.json` — JSON Schema definition
- `types/threat-signal.ts` — TypeScript types (optional convenience)
- `examples/` — Example payloads

## License
Apache-2.0
