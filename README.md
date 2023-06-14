# hydroturf
programs for triggering reconyx camera based on inundation monitoring in a channel using loggers and sensors from Campbell Scientific

## directories:
* `progs` - CRBasic program files
  * first use programs:
    * `Bisbee-F2-channel head.CR1` - program for CR1000 at head of channel
    * `hydroturn-bottom.CR300` - program for CR300 at channel basin
* `xml` - Device configuration utilities
  * `CR1000-43494-20230503.xml` - device configuration for CR1000
  * `CR300 Series-33034-20230503.xml` - device configuration for CR300
  * `RF401 Series-0-20230503.xml` - device configuration for CR1000 radio `RF401`
  * `RF401A Series-20230503.xml` - device configuration for CR300 radio `RF401A`
* `nwp` - network planner files
  * `bisbee-05012023.nwp` network planner for the entire bisbee CSci logger network that should be used first in lieu of the separate device configuration utility files

## Sensor Label Issues: (updated 06132023)
* Problem: Sensors are labeled in a way that is inconsistent with the program. 
* Solution: Move sensor labels around to create consistency with the program. 
## JL learning to use GitHub

* Inundation Sensors:

| Label # | Program # |
| 1 | 3 |
| 2 | 2 |
| 3 | 1 |


* Pressure Transducer: 

| Label # | Program # |
| 3 | 2 | 
| 2 | 1 | 
| 1 | 3 | 


## documentation and diagrams

### CR1000 Wiring Diagram and Info
![Image](./media/Wiring_Description_CR1000.jpg)

### CR300 Wiring Diagram and Info
![Image](./media/Wiring_Description_CR300.jpg)
