# Copper Cables and Connectors

1. Shielded twisted pair cabling protects it from EMI 
2. Drain Wire  
3. Solid: conducts signals better, prone to break 
4. Stranded: more flexiable, use for patch cables 
5. Cable categories
	- tighter twists and added shielding contribute to higher supported bandwidths 
	- Cat 5: supports 100 MB
	- Cat 5e: supports 1 GB per second
	- Cat 6: Supports up to 10 GB network for short runs
	- Cat 6a: Supports 10GB with more shielding.
	- Cat 7: Supports 10GB, shielding on each twisted pair and between, GG45 and TERA connectors.
	- Cat 8: 40 GB and 2 gigahertz. 
6. Connectors
	- Rj11: telephones, four connectors and supports up to two pairs
	- RJ45: Ethernet, eight connectors supports up to four pairs of copper wires. 
	- RJ48C: One for transmitting and one for receiving. Used for T1 WAN links. 
	- GG45: Cat 7 cabling 
	- TERA: not compatible with RJ45 or GG45
7. Coax
	- implemented in BUS network 
	- Inner conductor
	- PVC Insulator
	- Mesh shield
	- PVC sheath
	- Advantages: resist EMI
	- Disadvantage: expensive, thick and hard to install
	- Cable Grades: RG58 for Thinnet (10Base2) 50 ohms. RG-59 for cable TV 75 ohms, RG-6 satellite TV and cable modems with solid copper with 75-ohms. 
	- Connectors: BNC bayonet mount with two side lugs to lock in connection. F-type connector for cable tvs and satellite. 


## Key terms

- Crosstalk: DEF unwanted transfer of signals between communication channels
- Unshielded twisted pair UTP: DEF has grounded outer copper shield around the bungle of twisted pairs or around each pair. Provides EMI protection.
- Shielded twisted pair: DEF STP has a grounded outer copper shield around the bundle of twisted pairs or around each pair. Provides added protection against EMI
- Plenum space: DEF pathway that allows for airflow needed by heating and air con, dropped celling or raised floor
	- Plenum rated cables use insulation that is fire resistant and non toxic when burned
	- Must use plenum rated cables in plenum spaces

- Riser Space: DEF area connects multiple floors where cables can be run 
	- can use plenum rated cables in riser spaces
	- should never use riser rated cables in plenum spaces

- Wavelength division multiplexing WDM: DEF joins several light wavelengths (colors) into a single strand of fiber by using different wavelengths of laser light

## Fiber Optic
- Cladding reflect the light to not leave the glass or plastic core
- Fiber is expensive
- Difficult to work with 
### Single Mode
- Yellow
- Small diameter 8-10.5 micros
- light enters single path
- Less affected by modal dispersion, longer
- 10Gbps over 80 km
- higher speed
- precise connections
- higher cost electronics 

### Multi Mode
- orange or aqua
- Aqua preforms better at higher speeds and longer distances. 
- larger diameter 50-100 microns in diameter 
- light might bounce in the side, modal dispersion, and longer the cable length the greater the distortion. 
- shorter distances 
- slower speeds
- simpler connections
- 100 mbps up to 2 km and 1000 mbps up to 1000 meters. 10 Gbps up to 500 meters 
- lower cost electronics
- 850 nm and 1300 nm wavelengths

### Wavelength Division Multiplexing WDM
- different color of light entering the fiber 
- allows for different directions of light for data, can multiplex 160 signals
- Long haul and high speed, 16 tbps, uses single mode fiber 

### Connectors
- ST connector: single mode and multi mode, keyed bayonet connector, set and twist, needs polishing as part of assembly process
- SC Connector: single mode and multi mode, push on and clip, set and click, needs polishing as part of assembly process
- LC connector: single mode and multi, lift and click, they use a housing and latch system similar to RJ45 UTP connector, half the size of standard connectors. Use one piece bayonet connecting system, can be used with either fiber optic or copper cabling 
- MTRJ connector: single mode and multi, send and receve in one fiber., use metal guide pins to ensure accurate alignment 
- FC connector: only single mode

### Polish rating 
- Physical contact or PC polishing, with slight curvature when the cable end is mated to the connector. 
- SPC Super physical contact and ultra physical contact Upc uses higher grades of polish 
- Angled physical contact APC has 8 degree cut, only use angle polished connectors which are always green

### Simplex Duplex Patch
- Simplex: only need one fiber cable to communicate, can transmit and receive over a single fiber. 
- Duplex = two strands with two connectors at each end
- ST to LC and ST to SC and SC to LC are common conversions

### Media converters 
- Single or multi mode fiber to copper ethernet 
- single or multi mode to coax 
- single mode fiber to multi mode fiber
