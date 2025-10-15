# pg-client-toolkit
Pixelated Bot for DO/PG (works for almost all private servers with flash client) - needs botfather.io to run.

Technical features:
Template Matching / Blob Detection for Buttons, Icons, Windows
Minimap-Telemetry: Level/Position calculation, Inner/Outer-Rects, Pixel-Isolation
Pathfinding: Dijkstra-Algorithm Map-Graph → Waypoints + correct gate-coordination
FSM + Scheduler: periodic checks (Client/PET/Map/HP), Timeouts, Backoff
Resilience: Auto-reconnect, auto-revive, low/critical HP handling, edge case detection
Modular components: Client, Minimap, Navigator, Ship, PET, Collector, Hunter, Scheduler
Deterministic image processing: HSV isolation, pixel equality, reference images
