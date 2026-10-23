# Matlab|Simulating Electric Vehicle Charging and Discharging [Charging Order, Voltage Fluctuation Power Generation, Battery Buffer]

​  
1. Overview of Electric Vehicles (EV)
The diagram below illustrates the scenario of large-scale EV (Electric Vehicle) decentralized access to the distribution network. The management framework for EVs is divided into three levels: distribution network agents, local agents, and EVs. Distribution network agents are distributed across the high and medium voltage HVIMV (High Voltage Medium Voltage) substation layers, responsible for the safe and stable control of the distribution network as well as the orderly coordination control of EVs; local agents are located in the medium and low voltage MVLV (Medium Voltage Low Voltage) substation layers, responsible for the control of regional EV charging loads. Charging stations are connected under the distribution transformers, with the distribution transformer under which, besides the EV load EVL (EV Load), there are also conventional residential loads RL (Residential Load).
Editor
2. Summary of all codes for electric vehicles
3. Simulation of Electric Vehicle Charging and Discharging [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering] 3.1 Operational Results Edit
Editor
Editor
Editor
Editor
3.2 MATLAB Code
info.date.min = datestr(data_24h(idx_min,1),'dd.mm.yyyy');\n  info.date.avg = datestr(data_24h(idx_avg,1),'dd.mm.yyyy');\n  info.date.max = datestr(data_24h(idx_max,1),'dd.mm.yyyy');\n  info.rad.min.j = raw24h{4}(idx_min,2);              % J/cm^2\n  info.rad.avg.j = raw24h{4}(idx_avg,2);              % J/cm^2\n  info.rad.max.j = raw24h{4}(idx_max,2);              % J/cm^2\n  info.rad.min.kwh = raw24h{4}(idx_min,2)*(100/60)^2; % Wh/m^2\n  info.rad.avg.kwh = raw24h{4}(idx_avg,2)*(100/60)^2; % Wh/m^2\n  info.rad.max.kwh = raw24h{4}(idx_max,2)*(100/60)^2; % Wh/m^2\n  info.pv.min = data_24h(idx_min,2);                  % kWh\n  info.pv.avg = data_24h(idx_avg,2);                  % kWh\n  info.pv.max = data_24h(idx_max,2);                  % kWh\n  
​  

## Images

![Matlab|Simulating the Charging and Discharging of Electric Vehicles [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering]](01.png)
![Matlab|Simulating the Charging and Discharging of Electric Vehicles [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering]](02.png)
![Matlab|Simulating the Charging and Discharging of Electric Vehicles [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering]](03.png)
![Matlab|Simulating the Charging and Discharging of Electric Vehicles [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering]](04.png)
![Matlab|Simulating the Charging and Discharging of Electric Vehicles [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering]](05.png)
![Matlab|Simulating the Charging and Discharging of Electric Vehicles [Charging Order, Voltage Fluctuation Power Generation, Battery Buffering]](06.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
