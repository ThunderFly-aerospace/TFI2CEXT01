## What is TFI2CEXT? 

TFI2CEXT01 is a device or module, that contains an I2C bus buffer, the electronic component that enhances the signal on an I2C bus. The buffer creates a signal that is less prone to interference or large capacity of wires which is a common issue among usual I2C devices. Thanks to this feature, it is possible, for example, to elongate the I2C bus or connect more devices to one I2C bus. 

TFI2CEXT is designed directly for use in drone avionics. For this purpose, for example, it features a JST-GH connector with a pinout corresponding to the Pixhawk standard on both input and output.

## What makes TFI2CEXT special? 

ThunderFly I2CEXT device is unique in that it can be connected directly (without major changes) to the infrastructure of drones based on the Pixhawk standard.

## What are TFI2CEXT main features?
  
  * Input Power status LED indicator
  * Optional possibility of soldering pass-through I²C connectors to allow a daisy chain topology
  * Ability to isolate I2C bus segments by disconnecting frozen devices (Frozen devices are automatically attempted to reset)
  * Capability to handle a master and a slave bus sides differently
  * The extender is capable to perform a device reset if it seems to be frozen
  * READY signal indication of the correct connection of both I2C bus sides

The main reason for developing TFI2CEXT was that we repeatedly experienced a state when an I2C bus on drones was not reliable enough to be used safely. After developing our device the situation improved significantly and the problems with communication on the I2C bus disappeared.

## How TFI2CEXT could be used?

Using the I2C extender is very simple - it works by plugging into the bus, preferably into the middle of the bus wire's longest section. The PCB can be fitted with JST-GH connectors from both sides, the connectors are connected in parallel. This allows the TFI2CEXT PCB to act as a small I2C hub. There are 2 input connectors (before the I2C buffer) and 2 connectors enhanced by the I2C buffer.

The module contains 2 LED diodes. One indicates the presence of a power supply and should be lit all the time the power supply is present. The second - READY LED - lights up only if both sides of the bus are connected, the module is functional and ready to enhance the I2C bus transmissions.

### Compatibility

The bus buffer does not need any software configuration. Thanks to this, it can be used with any Pixhawk autopilot compatible firmware like [PX4](https://px4.io/) or [Ardupilot](https://ardupilot.org/) additionally the usage is not limited to UAVs only.

## What package includes

- TFI2CEXT01A
- Two spare JST-GH PCB connectors (only two connectors are soldered on PCB by default)

## Accessories

### I2C cables
I2C cables for connecting to the autopilot are not included in the package. You will need to purchase the cables separately from our [tindie catalog](https://www.tindie.com/stores/thunderfly/). We offer high-quality cables that are compatible with the [Pixhawk standard](https://raw.githubusercontent.com/pixhawk/Pixhawk-Standards/master/DS-009%20Pixhawk%20Connector%20Standard.pdf) and with a [ThunderFly color](https://docs.px4.io/main/en/assembly/cable_wiring.html#i2c-cables) scheme for easy signal identification. Our cables are specifically designed with improved resistance to electromagnetic interference and made with silicone insulation that makes them highly flexible.

  * Length 15 cm - [TFCAB15I2C01](https://www.tindie.com/products/thunderfly/tfcabxxi2c01-i2c-cable-for-pixhawk-drones/)
  * Length 30 cm - [TFCAB30I2C01](https://www.tindie.com/products/thunderfly/tfcabxxi2c01-i2c-cable-for-pixhawk-drones/)
  * Length 45 cm - [TFCAB45I2C01](https://www.tindie.com/products/thunderfly/tfcabxxi2c01-i2c-cable-for-pixhawk-drones/)
