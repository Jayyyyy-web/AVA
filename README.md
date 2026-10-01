# Project AVA

A personal concept exploration of **commercial jet-engine efficiency** — how a turbofan turns fuel into distance, and where every percent of efficiency is actually won.

> Educational concept. Figures are representative of real, public-domain engines and are intended for understanding, not as a design specification. No weapons content.

## Pages

| File | What it is |
|------|------------|
| `index.html` | Landing page — the concept, the efficiency levers at a glance, key numbers |
| `explainer.html` | The engineering — thermal vs propulsive efficiency, bypass/pressure ratio, turbine temperature, materials, trade-offs, reference numbers |
| `engine-3d.html` | Interactive 3D turbofan cutaway (three.js) with animated airflow and stage-by-stage notes |

## Running it

**In VS Code:** press **F5** and pick a configuration (Home / 3D Cutaway / Engineering).
These open the page directly in a browser via `.vscode/launch.json`.

**Or:** just open any `.html` file in a browser, or use the Live Server / Live Preview extension.

> The 3D page loads [three.js](https://threejs.org/) from a CDN, so you need to be online when you open it. If you want it to work fully offline, bundle three.js into the repo (ask and it can be set up).

## Topics covered

- Overall efficiency = thermal × propulsive
- Bypass ratio and why moving more air gently beats a fast jet
- The geared turbofan trick (decoupling fan and LP turbine speeds)
- Overall pressure ratio and turbine inlet temperature
- Materials & cooling: superalloys, film cooling, thermal barrier coatings, CMCs
- Weight & aerodynamics (composite fan, tip clearances)
- The frontier: open / unducted fans (e.g. CFM RISE), SAF and hydrogen
- The trade-offs behind every lever

## Sources

Representative figures drawn from public sources including Wikipedia
([Turbofan](https://en.wikipedia.org/wiki/Turbofan),
[CFM RISE](https://en.wikipedia.org/wiki/CFM_International_RISE),
[PW1000G](https://en.wikipedia.org/wiki/Pratt_%26_Whitney_PW1000G),
[GE9X](https://en.wikipedia.org/wiki/General_Electric_GE9X)) and manufacturer announcements.
