## Subsystems

Source of research: https://mars.nasa.gov/MPF/rover/about.html

- navigation
  - including sensor for navigation, such as ultrasound, cameras etc.
  - including core computer unit, for processing the data for computer vision
  - computer for planning navigational routes
- mobility
  - the driving mechanism e.g. motors, enginges
  - the (micro)controllers for them
- life support
  - oxygen and air treatment
  - water recycling systems
  - waste management
  - thermal (heating)
- telecommunication
  - including antennas and physical hardware
  - communications with base?? ship??
  - computers 
- power
  - managing the power in the rover
  - how electric power is flowing in the vechile
- sensory
  - manages the sensors and tools used for scientific research
  - analysis the data from them
  - stores (redundantly)

## Risk analysis

Identify the most crucial parts of the system. One is for sure: the power subsystem. 
The subsystem responsible for power is crucial, as if there is no power we cannot expect 
any other subsytem to work, so redundancy here is required, either by an extra emergency battery, a fossil fuel burning generator or hydrogen cells should be added.

After the rover has redundant energy source, the life support systems shoudl be checked.
The fact that the astronauts should be kept alive is a must, so life support systems should
have redundancy, at least on the level of oxygen and air treatment and fresh water providing. Besides having this double redundant system astronauts can always take up their
scafanders, so this is actually a truple redundancy.

Besides the above mentioned two important subsystems, the third in line should be 
the telecommunications system, as researchers and the crew of the rover can ask
for help if neccessary from the rover.
