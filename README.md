# Last-Mile PSW

A day-planning app for personal support workers (PSWs) — the people who travel
from home to home providing care.

## The problem

A PSW visits a series of clients in their homes over a shift. Each visit takes
as long as the care takes. Some clients have to be seen within a particular
window. The shift has an end, and a break has to fit somewhere. When one visit
runs long, everything after it has to be rearranged — often between stops.

## What the app does

- Works out the order of the day's visits and the route between them.
- Re-plans when the day changes, so one visit running long doesn't quietly
  break the ones after it.
- Shows what a plan costs: waiting time, late arrivals, overtime.
- Keeps working without a signal. Maps, routing, and spoken turn-by-turn
  directions are stored on the phone, so it still works in a basement
  apartment or a stairwell.

![The app showing an offline map of Toronto](assets/offline-map.png)

## Status

An iOS prototype, still in development, built and tested on iPhone. It is not a
clinically validated product and is not in use with real clients. Schedule
credentials are held in the phone's encrypted storage.

Not yet finished: Android routing, and lock-screen (Live Activity) integration.
Offline maps only cover regions that have been loaded onto the device, and
travel-time estimates and map drawing have known limits.

Screenshots and a demonstration video are in preparation, using fictional
visits — see [how the demo is recorded](docs/DEMO.md).

Contact: [AubinGil on GitHub](https://github.com/AubinGil).
