# AzureIoTEdgeDeviceAccess
This sample project is a demonstration of the Azure IoT Edge Module, which controls the GPIO of the Host OS.
The device uses Raspberry Pi (Raspbian), and the source is written in Python.
The core part should be set to the privilege to access the host OS in the module createOption part of the distribution manifest part.
"createOptions": "{\" HostConfig \ ": {\" Privileged \ ": true}}"