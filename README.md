ESP32 Setup → Wi-Fi Connect → Blynk Connect
         │
         ├─> Timer every 1s → blinkCount()
         │        │
         │        ├─> Update temperature/humidity
         │        ├─> Store in Preferences
         │        └─> Send to Blynk V1/V4
         │
         ├─> Terminal Input V2 → Fan ON/OFF
         │
         └─> Button V3 → Reset readings & preferences
