# im-telemetry-spoof
Node server to expose fake telemetry data over websocket. Based on the [OpenMCT telemetry adapter tutorial](https://nasa.github.io/openmct/docs/tutorials/#telemetry-adapter), and intended to be used to demonstrate functionality of illini-motorsports-telemetry.

## Dependencies
node.js (LTS v6.9.5 tested and working)

## Setup

    npm install ws
    npm install wscat
  
## Usage
    node app.js

## Confirming Functionality
    wscat -c ws://localhost:8081

When message appears saying "connected (press CTRL+C to quit
    
    dictionary

Ensure that the dictionary syntax is returned.