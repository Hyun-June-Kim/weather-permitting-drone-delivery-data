# Weather-Permitting: Drone Delivery Data

**"Weather-Permitting: Service Level Consistency in Drone Delivery"**  

## Data Contents

### Weather Data (`Weather_Base/`)
Hourly meteorological data (temperature, precipitation, wind speed) from 
4 USNWS weather stations near FAA-approved drone hubs in the 
Dallas-Fort Worth metroplex, January 1 – December 31, 2023.
Stations: ADS, HQZ, TKI, F46

### Weather Data — Sensitivity Analysis (`Weather_SA/`)
Modified HQZ weather data for the temperature tolerance sensitivity 
analysis (Section 5.4.2), with upper thresholds raised to 42°C and 44°C.
  Weather_SA/42/  — 42°C tolerance (12 monthly files)
  Weather_SA/44/  — 44°C tolerance (12 monthly files)

### Demand Data (`Customer/`)
Simulated customer order data for 1,000 customers per drone hub 
(TX0005/ADS, TX0007/HQZ, TX0010/TKI).
