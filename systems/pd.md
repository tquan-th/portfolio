# Automated USB-C PD and I/O Test Fixture
This fixture was designed to test USB-C Power Delivery (PD) protocols and all Type-C data lines through a device that can both source (supply) and sink (drain) power. As both an end-of-line and hardware-in-the-loop (HIL) test, the system can be used for production and design validation testing (DVT) of the device under test (DUT).

## Design Requirements
* Run source PD through the DUT
* Run sink PD through the DUT
* Check USB 3.2 throughput
* Check the above in flipped orientation
* Check USB 2.0 throughput

## Context
USB-C is the most unified connector in consumer electronics. Unlike its precedessors, it can also reach speeds up to 10 gigabytes per second (USB Gen 3.2) while retaining backwards compatibility with USB 2.0 (5 megabytes per second) connections. This is made possible via 24 physical pins inside the connector. It can also support DisplayPort signals.
