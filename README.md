# f042_usarti2c_mx
MX generated project with USB device, I2C, usart1 and usart2 enabled.

In MX project the size of heap and stack have been reduced significantly.
Otherwise the build fails at the linker with the CDC middleware added 
to the project.

Also learned that the F04 device would need to pause long enough for the host 
to install the VCP device upon connection before the vcp port is available
to the device.


