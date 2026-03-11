fetch_sim_info is responsible for reading SIM card details from the cellular modem.
It collects important parameters such as:

SIM ICCID

IMSI number

Network operator name

Signal strength (RSSI / CSQ)

Network registration status
This function is used during system initialization to ensure that the SIM card is present, active, and connected to the network before MQTT / internet communication starts.
