# GeyserWorx-Monitoring

This app can be run from Node-Red Desktop for monitoring and basic control of a [GeyserWorx](www.geyserworx.co.za) water heater control system.

https://nodered.org/ or https://sakazuki.github.io/node-red-desktop/


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
- Import settings.js settings into your existing settings.js file to enable persistent storage context.
- Install the following nodes required for this configuration:
  - node-red-contrib-deduplicate-adv
  - node-red-contrib-mqtt-dynamicsub
  - node-red-dashboard
- Open GeyserWorx.json.
- Deploy the solution.
- Navigate to Dashboard and fill out settings required from the Configuration page.
- These include:
  - IP Address of the GeyserWorx unit on your network.
  - Wifi Serial number located on the bottom left side of the GeyserWorx unit.
  - Hot water heater vesel heating element size. (kW)
  - Utility power rate per unit.
- Click submit

