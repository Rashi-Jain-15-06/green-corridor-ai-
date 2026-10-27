# Green Corridor AI — Source Code

## Run
1. Extract this ZIP.
2. Open `index.html` in a modern browser.
3. Choose start and destination, select Normal or Busy traffic, then click **Simulate corridor**.

No installation, build step, API key, or internet connection is needed.

## Files
- `index.html`: UI and controls
- `styles.css`: responsive layout and soothing sage/off-white/blue palette
- `app.js`: fictional graph, Dijkstra shortest-path routing, SVG route rendering, delay comparison, validation, event log, reset and copy summary
- `PROJECT_SPEC.md`: concept, scope and limitations

## How it works
A weighted graph represents seven fictional junctions. Dijkstra's algorithm calculates a shortest path. A toy timing model compares assumed per-junction delays in a baseline and coordinated scenario.

## Important limitations
This is a simulation-only hackathon prototype. Road data and timing values are fictional assumptions, not measured results. It does not use a real AI/ML prediction model, GPS, live traffic data, emergency dispatch, or traffic-light controllers. Do not use it for real emergency operations. Real deployment would require authorized integrations, traffic authority oversight, safety engineering, rigorous validation and approvals.
