#nrf5-ble-tutorial-characteristic
This example is meant to be used togheter with the tutorial "BLE Characteristics, a beginner's tutorial" found on https://devzone.nordicsemi.com/tutorials/17/. The purpose of this tutorial is to get you started with the basics of BLE, the nRF5x DK, and the SDK. More specifically we will go through the bare minimum of steps to get your first complete BLE application up and running. My goal in this tutorial is to have as little theory as possible, but still get you up and running with a “springboard” application. While doing this we will have a brief look at the attribute protocols, how services and characteristics are structured, and how it all looks in Master Control Panel. Hopefully it will be a fun way to get started with something functional, and maybe inspire you to go further with BLE. The tutorial is intended to be a natural continuation of the "BLE Services, a beginner's tutorial". 

# Requirements

* nRF51 DK or nRF52 DK Kit
* nRF51 Dongle
* Master Control Panel (MCP). You can also use the Master Control Panel found in the nRF Toolbox app for Android or the LightBlue app for iPhone.
* Keil v5.12 or later
* nRFgo Studio
* SDK v11.0.0.
* For nRF51 DK use SoftDevice S130 V2.0.0 for nRF52 DK use S132 V2.0.0.
* Example files.

Other kits, dongles and software versions might work as well, but this will not be covered here.

To compile it download the project files and copy the folder "nrf5x-ble-tutorial-service" to "your_SDK_folder\examples\ble_peripheral".

Please post any questions about this project on https://devzone.nordicsemi.com/questions/.

# About this project
This application is one of several applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty.
However, in the hope that it still may be useful also for others than the ones we initially wrote it for, we've chosen to distribute it here on GitHub.
The application is built to be used with the official nRF5 SDK, that can be downloaded from http://developer.nordicsemi.com/.