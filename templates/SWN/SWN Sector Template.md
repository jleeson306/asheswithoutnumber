```varinote
system_name::System Name
system_star_type|dropdown::Star Type|M-Red .3Sr,K-Orange/Red 0.8Sr,G-White/Yellow 1Sr,F-Blue/White 1.3Sr,A-Blue 1.7Sr,B-Blue 5Sr,O-Blue 10Sr,Binary System,Black Hole,Neutron Star, Wormhole
system_exchange_satellite|toggle::Exchange Satellite|true
system_refueling_options|dropdown::Refueling Options|None,Scoopable Gas Giant, Fuel Station, Scoopable or Station
system_hazards|dropdown::Hazards|None,Sensor Interference,Magnetic storms,Debris fields,Micro-asteroids,Gravitational Anomalies
system_traffic|dropdown::Traffic|None,Monthly,Weekly,Daily
system_authority::System Authority
system_security_level|dropdown::Security Level|Lawless,Light Patrols,Monitored,Secure
```
### {{$system_name}}
- **Star Type:** {{$system_star_type}}
- **Exchange Satellite:** {{$system_exchange_satellite::Yes,No}}
- **Refueling Options:** {{$system_refueling_options}}
- **Hazards:** {{$system_hazards}}
- **Traffic Frequency:** {{$system_traffic}}

- **System Authority:** {{$system_authority}}
- **Security Level:** {{$system_security_level}}
- **Faction Presence:** 
- **Military Assets:** 
- **Industrial Assets:** 
- **Scientific Assets:**