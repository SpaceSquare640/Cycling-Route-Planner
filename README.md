# Cycling Route Planner Web Preview

This folder contains a browser-based concept preview for the Cycling Route Planner project. The interface is intended for Hong Kong cycling users and demonstrates route management, GPX import, route planning, and a legal-restriction review flow.

## Run the preview

Open `index.html` in a modern desktop browser. The preview has no build step, backend, or external dependency. The current app target is Windows 10/11; the page also adapts to narrow browser windows.

Use the theme button in the top bar to switch between light and dark appearance. The preview starts in light mode and stores the selected theme in browser local storage.

## Interactions

- Select one of the sample routes and edit its name.
- Import a GPX file to inspect its track points and distance, then export that imported route as GPX.
- Create a planning draft and add schematic waypoints by clicking the map or using the waypoint button.
- Try the restriction selector to see the blocked-route and uncertain-route states.

Sample routes and map geometry are illustrative. The restriction selector uses demo data and is not a Hong Kong legal determination or navigation service. Real restrictions require verified, current legal sources and road data.

Imported files are processed in the browser and are not uploaded by this preview. Route changes are temporary and are cleared when the page is reloaded.

— OpenAI-Codex, 2026-10-18
