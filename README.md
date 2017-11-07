# Lightpack-HASS
Lightpack component support for the Home Assistant platform. Interacts via a series of telnet commands.

Takes in 3 parameters:
- IP Address of machine running Prismatik
- Port Number
- API Key

The 'Enable Server' checkbox, the port number and the API key are all found in Prismatik's Experimental tab.

See the custom component [documentation](https://home-assistant.io/developers/component_loading/) for Home Assistant installation info. Basically this goes to /config/custom_components/lights/lightpack.py
