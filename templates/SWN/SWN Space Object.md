```varinote
object_name::Object Name
object_type|dropdown::Type|Gas Giant,Rocky Planet,Ice Planet,Rocky Moon,Ice Moon,Asteroid Belt,Asteroid Cluster,Nebula
object_size|dropdown::Size|Tiny,Small,Medium,Large,Massive
object_satellites|slider::Moons or Satellites|0,128,1,0
object_gravity|dropdown::Gravity|None,Micro Gravity,Moon-Like,Earth-Like,Strong,Extreme
object_atmosphere|dropdown::Atmosphere|None,Breathable,Breathable(Respirator),Corrosive,Toxic,Biological Hazard
object_temperature|dropdown::Temperature|Frozen,Cold,Temperate,Hot,Burning
object_radiation|dropdown::Radiation Level|Nominal,Light,Major
object_terrain|dropdown::Terrain|Desert,Oceanic,Volcanic,Jungle,Metallic Core,Ice Fields,Rocky Belt,Artificial Superstructure
object_resource_density|dropdown::Resource Density|None,Poor,Moderate,Rich,Extreme
object_weather|dropdown::Weather|Calm,Stormy,Erratic,Seasonal,Unpredictable
object_visibility|dropdown::Visibility|Clear,Dusty,Foggy,Electromagnetic interference,Radio opaque
```

### {{$object_name}}
- **Type:** {{$object_name}}
- **Position:** {{$object_type}}
- **Size Class:** {{$object_size}}
- **Moons / Satellites:** {{$object_satellites}}
- **Gravity:** {{$object_gravity}}
- **Atmosphere:** {{$object_atmosphere}}
- **Temperature:** {{$object_temperature}}
- **Radiation Level:** {{$object_radiation}}
- **Terrain / Composition:** {{$object_terrain}}
- **Resource Density:** {{$object_resource_density}}
- **Weather Patterns:** {{$object_weather}}
- **Visibility Conditions:** {{$object_visibility}}