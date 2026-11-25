# Westinghouse Generator Controller

This Controller controller is based on csvanholmPicoW design, thank you Carsten!
## What makes this design different? 
- Meant to be used with Home Assistant, however shouldn't be difficult to make is an standand alone WebUI like in Joe Hershberger's implementation.
- Outage detection is done using the battery tender. Thus, this only works if you have an ATS with subpanel like mine [Nature's Generator 50A ATS](https://naturesgenerator.com/products/50a-automatic-generator-transfer-switch) which I hightly recommend instead of a full house ATS that would restore the battery tender. A future version might include an option for a external dry contact.   
- ESP32 based, specifically SEEED Studio XIAO, there are multiple pin compatible modules, they are easy to get from Seeedstudio, Amazon, Digikey, Mouser etc. I would recommend the ESP32-C3 or C6 just for the external antenna connection.

## Hardware
- GX20 - 7 Pins

# References:
 - [Reddit Custom Controller Build](https://www.reddit.com/r/OffGrid/comments/mxygik/westinghouse_generator_automatic_transfer_switch/)
 - [csvanholm/WestinghousePicoW](https://github.com/csvanholm/WestinghousePicoW)
 - [jhershbe/westinghouse-smart-switch-adapter](https://github.com/jhershbe/westinghouse-smart-switch-adapter)
