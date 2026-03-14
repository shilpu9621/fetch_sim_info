### fetch_sim_info

**Purpose:**  
The `fetch_sim_info` function reads SIM card and network information from the cellular modem. It is used to verify SIM availability and network connectivity before starting cloud communication.

**Details Collected:**  
- ICCID (SIM identifier)  
- IMSI (Subscriber identity)  
- Network operator name  
- Signal strength (RSSI / CSQ)  
- Network registration status  

**Usage Example:**
```python
sim_info = fetch_sim_info()
print(f"ICCID: {sim_info.iccid}, Operator: {sim_info.operator}")
