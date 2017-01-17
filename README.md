Sensiphus
=========

A data relay service for reading and exporting IoT-like sensor data.

**THIS IS WORK IN PROGRESS...**

This is intended to collect data from devices and relay it to other
destinations. Sensors/devices can be (hardware) IoT ones like those
measuring e.g. humidity and temperature in a network. But they can also
be purely virtual ones like software running on some computing device.

Supported destinations include stdout on the command-line, CSV files
and databases, as well as remote HTTP, MQTT and ZMQ.

Supported hardware devices consist of a Raspberry Pi Sense HAT and a
Pimoroni Enviro-pAHT. Both can be mocked and provide some fake time
series data.

The command-line interface supports specifying one scheduler, one device,
and one exporter. More complex configurations can be specified in the
``config.yml`` file.

More to come... Please stay tuned!
