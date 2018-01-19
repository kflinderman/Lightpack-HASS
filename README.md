# Lightpack-HASS
Lightpack component support for the Home Assistant platform. Interacts via a series of telnet commands.

Takes in 3 parameters:
- IP Address of machine running Prismatik
- Port Number
- API Key (leave blank if not using)

The 'Enable Server' checkbox, the port number and the API key are all found in Prismatik's Experimental tab.

If you want to change the Lightpack's profile, there is a new Service Call registered under lightpack called `set_profile`. The JSON payload would look something like `{ "profile":"Default" }`.

See the custom component [documentation](https://home-assistant.io/developers/component_loading/) for Home Assistant installation info. Basically you place the file into  `/config/custom_components/light/`
