# pg-client-toolkit
Pixelated Bot for DO/PG (works for most Flash-based private servers) — requires botfather.io to run.

## Technical features
- **Template Matching / Blob Detection** for buttons, icons, windows
- **Minimap Telemetry:** level/position calculation, inner/outer rects, pixel isolation
- **Pathfinding:** Dijkstra-based map graph → waypoints + correct gate coordinates
- **FSM + Scheduler:** periodic checks (Client/PET/Map/HP), timeouts, backoff
- **Resilience:** auto-reconnect, auto-revive, low/critical HP handling, edge-case detection
- **Modular components:** `Client`, `Minimap`, `Navigator`, `Ship`, `PET`, `Collector`, `Hunter`, `Scheduler`
- **Deterministic image processing:** HSV isolation, pixel equality, reference images

