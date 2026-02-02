The nRF52840 microcontroller actively acts as a communication bridge that transmits and receives data to and
from a mobile phone via a Bluetooth Low Energy connection. When you type commands on the computer, 
the nRF52840 captures this information and transmits it wirelessly over Bluetooth directly to the smartphone application using the Nordic UART Service. 
Simultaneously, the microcontroller listens for incoming Bluetooth packets sent from the phone and
immediately receives this data to relay it back to the computer via the USB interface, effectively establishing a 
two-way wireless link where the nRF52840 is responsible for all over-the-air data exchange.
