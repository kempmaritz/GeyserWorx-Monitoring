# GeyserWorx-Monitoring

This app can be run from Node-Red Desktop for monitoring and basic control of a GeyserWorx (www.geyserworx.co.za) water heater control system.
https://sakazuki.github.io/node-red-desktop/

## Basic functionality include:
- PC and AC temperature setpoint control
- PV and AC enable/disable
- PV and AC amperage indication
- PV and AC power generated total
- PV and AC cost/saving
- %PV usage
- Carbon footprint saving
- Alarm monitoring
- Timers setting (Enables when GeyserWorx is allowed to heat the water from AC power.)
- Basic 1 day graph of heating performance

## Node-Red Desktop Settings
Nodes exclude:
32-udp.js
node-red-node-sentiment

## Usage
Import settings.js settings into your existing settings.js file to enable persistent storage context.
Open GeyserWorx.json.
Deploy the solution.
