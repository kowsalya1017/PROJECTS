# AMBULANCE BOOTH

## OVERVIEW
Design Thinking is a cyclical process aimed at gaining deep insights into the user's needs, questioning assumptions, and reframing challenges to discover fresh strategies and solutions. It emphasizes a solution-oriented approach to problem-solving, making it relevant to any context that requires innovative thinking. This method empowers even the most conventional thinkers to generate new and creative ideas. By following its steps, anyone can unlock their creative potential. Essentially, it is a structured, human-centered approach to innovation with a clear purpose.

## COMPONENTS
The components used in this setup include:
- GSM module
- SIM 800 module
- Network indicator LED
- 12V DC power input
- SIM card slot
- RS232 interface
- SMA Antenna
- USB 2.0 cable for connectivity in the PuTTY application

## WORKING
In the GSM module, both SMS and calls can be transmitted using its transmitter, receiver, and ground connections. The module converts AT commands into serial data. Since the GSM module generates TTL (Transistor-Transistor Logic) output, it cannot be connected directly to a microcontroller. To interface it with a laptop, the RS232 serial port is used.In this module, AT commands are converted into serial data, and with the appropriate program on the laptop, messages and calls can be sent. The module includes a 12V adapter jack for power supply and an RS232 port for laptop connection. Beneath the RS232 section, there are transmitter, receiver, and ground pins.The module also features a SIM slot, microphone, and speaker for communication, and an antenna for improved signal reception. To power the module, the 12V adapter is connected, and a 2G SIM card is inserted into the SIM socket, as the module supports 2G networks. For laptop connectivity, a USB 2.0 cable is connected from the RS232 port to the laptop. The PuTTY application is then used for coding, and the type of USB 2.0 cable is selected in the PuTTY app.

## CONCLUSION
In conclusion, we have developed a mini project titled "AMBULANCE BOOTH," designed to be practical and meet the needs of consumers during emergencies. This system will greatly benefit rural populations by ensuring timely ambulance services, helping to save lives by responding within the crucial golden hour.
