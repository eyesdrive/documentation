# Understanding the Eyes

## Biosignals and the Electrooculogram


## The EyesDrive front-end

The EyesDrive front-end is composed by two main section: the biosignal amplifier and the application processor.

Both parts work toghether to interpret the EOG signal and trasmit it to third-party devices in a more comprehensible way.

### Biosignal Amplifier
The Biosignal Amplifier conditions the EOG signal to be sampled by the analog-digital converter in the SoC. 


The actual iteration of the EyesDrive front-end only supports recording one channel at a time. To the final user it means that only one movement axe out of two can be mapped. Future version of the front-end may include a second channel to map the user vision in a 2D space.

#### User safety

### System on a Chip
The EyesDrive front-end is powered by the Nordic nRF52832 SoC: a complete solution including an ARM Cortex-M0 processor clocked at 64MHz, a Bluetooth Low Energy 5.0 radio and essential peripherals to interface with the analog domain of the board.

#### Sight: The EyesDrive Operating System


#### BLE Interface


## Using the Front-End