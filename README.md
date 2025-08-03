# CH32V003 dev boards meant for breadboard use.  
They have a all of the chip connections brough out to a SIP header on one side of the board which can be plugged into the outer row of pins on a breadboard--leaving all of the rest of the board available for other components and routing.

All boards have USB-C connections for data and/or power.  The data is connected via two series resistors.  Not populating these allows the pins on the chip to be used for something else.

The on board 3.3V regulator can be left off and bypassed to run the board on Vbus power.  The regulator is used for when the D+/D- lines are connected to use use from the CH32V003 via rv003usb.  

The three pin header is for plugging in a debugger like the funprog or WCH Link-E.  It exposes Vcc, SWD, and GND.

New for V4:
- Change to the popular 1117 style regulator.
- Increase size of decoupling caps to 1206
- Move as many components to the front as possible (not an option on 8 pin) to improve manufacturability
- Add 16 pin variant by popular demand
<img width="1463" height="1120" alt="j4m6_front" src="https://github.com/user-attachments/assets/aa3d25e2-639d-4a14-8fb3-99749544a2b9" />
<img width="2210" height="716" alt="f4p6_front" src="https://github.com/user-attachments/assets/dd3b3e2b-076c-4ae7-ad35-079f41f31dd5" />
<img width="2220" height="902" alt="a4m6_front" src="https://github.com/user-attachments/assets/fcf3700b-1c65-4ef3-9d3a-e4955e8e33c4" />
<img width="2211" height="708" alt="f4u6_front" src="https://github.com/user-attachments/assets/8664d6a3-3f00-4b00-97ee-0c00e17bda77" />
