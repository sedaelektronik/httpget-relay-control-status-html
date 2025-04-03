# httpget-relay-control-status-html
Http get html web interface for relay control products. Requires special proxy.

* Control button names between lines 269 and 284 can be changed.

const RELAY_NAMES = [
 "RELAY-1", // Relay1 (Port B, bit 0)
 "RELAY-2", // Relay2 (Port B, bit 1)
 "RELAY-3", // Relay3 (Port B, bit 2)
 "RELAY-4", // Relay4 (Port B, bit 3)
 "RELAY-5", // Relay5 (Port B, bit 4)
 "RELAY-6", // Relay6 (Port B, bit 5)
 "RELAY-7", // Relay7 (Port B, bit 6)
 "RELAY-8", // Relay8 (Port B, bit 7)
 "RELAY-9", // Relay9 (Port D, bit 0)
 "RELAY-10", // Relay10 (Port D, bit 1)
 "RELAY-11", // Relay11 (Port D, bit 2)
 "RELAY-12", // Relay12 (Port D, bit 3)
"RELAY-13", // Relay13 (Port D, bit 4)
"RELAY-14", // Relay14 (Port D, bit 5)
"RELAY-15", // Relay15 (Port D, bit 6)
"RELAY-16" // Relay16 (Port D, bit 7)
];

* The device source page to be controlled can be selected with the ip variable in line 261:
const DEFAULT_IP = "169.254.1.2:3000/s";
