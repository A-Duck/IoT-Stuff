# Smart Charger

I made this smart charger so that I don't overcharge my devices and cook the batteries.

## Files
	* **smart-charger.yaml:** ESPHome config file
	* **Phone Automation.yml:** Home Assistant automation for phone that communicates with HASS
	* **Tablet Automation.yml:** Home Assistant automation for tablet that communicates with HASS
	* **BT Speaker Automation.yml:** Time based automation for devices that don't talk to Home Assistant


## Pin Mapping

**Relays:**

	* Relay 1 - Pin 4 - Inverted
	* Relay 2 - Pin 16 - Inverted
	* Relay 3 - Pin 17 - Inverted
	* Relay 4 - Pin 5 - Inverted

**LEDs:**

	* LED 1 - Pin 18
	* LED 2 - Pin 19
	* LED 3 - Pin 21
	* LED 4 - Pin 3

**Buttons:**

	* Button 1 - Pin 27 - Inverted - Mode: INPUT_PULLUP
	* Button 2 - Pin 26 - Inverted - Mode: INPUT_PULLUP
	* Button 3 - Pin 33 - Inverted - Mode: INPUT_PULLUP
	* Button 4 - Pin 32 - Inverted - Mode: INPUT_PULLUP