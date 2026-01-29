# Bookdarr Media Diagnostics

Central diagnostics repo for Bookdarr Media Server (BMS) and Bookdarr Media Reader. Diagnostics are opt‑in and stored in separate folders.

## Structure
- `/bms/` — server diagnostics
- `/reader/` — mobile app diagnostics

## Policy
- Diagnostics are opt‑in by default.
- Later hidden behind secret unlock in each app.

## Notes
Never store credentials or API keys in diagnostics.
