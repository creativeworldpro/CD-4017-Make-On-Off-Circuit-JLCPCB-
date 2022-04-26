The article is being published in collaboration with JLCPCB. They supply high quality PCBs at a very reasonable price.
They also can provide SMT circuit assembly.

We thanks to our sponsor JLCPCB  https://jlcpcb.com/RTA for sponsoring us PCBs for this project circuit.


Thanks to JLCPCB.

$2  for 1-4 Layer PCBs.

Get SMT Coupons - https://jlcpcb.com/RTA


The project is about, making a on-off circuit using only single push button switch. Using this SMT project circuit, you can control any 12v device easily. This project circuit helps you to on-off any circuit using only one push switch. 

This circuit can be operated only DC-12v power supply circuit. 

If you don’t have DC-12v SMPS circuit, you also can use 12v battery.


To make this circuit, we are using CD-4017 CMOS decade counter IC. The IC contains 16 legs.
Whenever a clock pulse is received at the clock input of the IC 4017 counter, 
the counter increments the count and activated the corresponding output pin.

Component List - 

To making this SMT project circuit, we are using some SMD components.  
The table below provides an overview of available components, sorted by component type. 
You can order your assembled SMT circuit form JLCPCB.

All components list have been given below –

1.	Resistor - 100k, 2.2K, 4.7K, 100 Ω (1/2 watt -  R1210)

2.	Diode – A7 (1N 4007 – SOD 123FL)

3.	Capacitor – 2.2µf/50v (SMD_4*5.4mm)

4.	Transistor – MJE 13003 (SOT-89-3)

5.	Push Switch – TS3625A 

6.	LED – (SMD_ 3.5x2.8x1.4mm)

7.	IC – CD4017 (SOP-16)


CD-4017 Pin Out - 

CD-4017 is used for low range counting applications. It can count from 0 to 10 (the decade count). 
It has 10 outputs that represent the number 0 to 9. The counter increases with one for every rising clock pulse.
After the counter has reached 9, it starts again from 0 with the next clock pulse.

The easiest way to create a decade counter is by connecting 10D flip-flops in series to create a shift-register. 
This is also known as a ring counter. One of the most popular hobbyist projects to build with this chip is the running LEDs circuit.

The LEDs blink in sequence from the first to last and then starts from the first again. LEDs are connected to each of the outputs and therefore appear to be “running” along a line.
	
  
Its 16 legs Pin Out can be seen above - 

1.	Pin-1: When the counter reads 5 counts then this pin 1 will become high which is output number 5.
2.	Pin-2: When the counter reads 1 count then this pin 2 will become high which is output number 1.
3.	Pin-3: When the counter reads 0 counts then this pin 3 will become high which is the output number 0.
4.	Pin-4: When the counter reads 2 counts then this pin 4 will become high which is output number 2.
5.	Pin-5: When the counter reads 6 counts then this pin 5 will become high which is output number 6.
6.	Pin-6: When the counter reads 7 counts then this pin 6 will become high which is the output number 7.
7.	Pin-7: When the counter reads 3 counts then this pin 7 will become high which is the output number 3.
8.	The ground is supply to this IC at Pin number 8.
9.	Pin-9: When the counter reads 8 counts then this pin 9 will become high which is output number 8.
10.	Pin-10: When the counter reads 4 counts then this pin 10 will become high which is output number 4.
11.	Pin-11: When the counter reads 9 counts then this pin 11 will become high which is the output number 9.
12.	This pin number is used to delay the counting operation. When the 10 clock cycles complete one full cycle complete and the carry bit will be used as a delay
13.	When the enable is low then the IC CD 4017 will perform its operation. So to make the IC on we will ground the enable pin and if we want to off the IC we will make it high when this pin is in the high state it will ignore the clock signal. It will work only when we make this pin to operate in a low state.
14.	This pin will operate on the positive edge of the clock. When the first clock pulse is detected pin 3 goes, for the next clock pulse pin 2 goes high like this sequence is formed. A sequence output will be formed Q0 to Q9.
15.	This pin will reset the counter from the beginning. The IC will operate when the Reset pin is in the low state and if we want to reset the counter we will provide high voltage.
16.	The voltage is supplied to this IC CD4017 through Pin number 16. The voltage range for this IC 3V to 15V for the IC to function.


Feature - 

•	High speed 16 pin CMOS Decade counter

•	Supports 10 decoded outputs

•	Wide supply voltage range from 3V to 15V, typically +5V

•	TTL compatible

•	Maximum Clock Frequency: 5.5Mhz

•	Available in 16-pin PDIP, GDIP, PDSO packages

•	The supply voltage of this IC is 3V to 15V.

•	It is compatible with TTL (Transistor -Transistor Logic).

•	The clock speed or operational speed of CD4017 IC is 5 MHz.

•	Output current is 19mA.

•	Power is about 10uW.

•	The IC has high noise immunity.



Application - 

•	Any counter circuit.

•	Decoders.

•	Binary Encounters.

•	For frequency division projects.

•	LED Flashing Light.

•	Digital dice circuit.

•	Remote control switches circuit.

•	LED chaser circuit.

•	Clap on-off switch, etc.

•	Divisible counting by N

•	Industrial and medical electronics

•	LED matrix circuits

•	LED chaser applications and LED based projects



Circuit Connection – Step 1

To make this circuit, 1st we need to connect IC 8th no leg with 13th no leg and connect 10th no leg with 15th no leg.

Now we connect diode with CD-4017 IC. We connect diode positive leg with 2, 4 and 7 no leg of IC.
Then we connect 2.2k, 4.7k and 100 Ω resistor with diode.
We connect 2.2k resistor with diode negative leg that is connected with IC 2no leg. 
Then connect 4.7k and 100 Ω resistor with diode negative leg that is connected with 4 and 7 no leg of IC.


Circuit Connection – Step 2

Now, we connect all resistors together and connect that resistor with Base leg 13003 transistor. 

Connect transistor “Emitter” leg with 8 no leg of IC. 

Connect 100K resistor with 13 and 14 no leg of IC. We need to connect capacitor with the circuit. 
Connect capacitor negative leg with 14 no leg IC and connect capacitor positive leg with 16 no leg of IC.

To control circuit, we connect push switch. Connect push switch one terminal with 14 no leg of IC. 


Circuit Connection – Step 3 

We are using 3v LED light. Then we make a series connection in these 4 pieces LED light.

Now connect LED light positive leg with push switch and connect LED negative leg with “Collector” leg of 13003 transistors.
	
It is the time to connect DC-12v power supply with the circuit. Connect DC positive voltage with 16 no leg of IC and connect DC negative leg with 13 no leg of IC.

Our circuit is completely ready for use now. Just plug-in power and enjoy the circuit. 

Steps to Order PCBs from JLCPCB - 

If you complete design of your PCBs, then it is time to order PCBs. To order best quality PCBs, just visit JLCPCB and click on the “QUOTE NOW” button.

Since 2006 JLCPCB continuously driven to become more efficient and to reduce costs. They promise to offer customers the most economic PCBs forever. JLCPCB makes cheapest but top quality PCBs possibly because of scale effect, extremely high production efficiency and less manpower cost.

You can order minimum 5 pieces PCBs for only $2 costs.

To order PCBs, make your Gerber file. Then drag and drop the Gerber file on the following box.

Click on “Gerber Viewer” button you can check the PCBs design. Make sure everything is good, then choose color, quantity and order your PCBs at very reasonable prices.

If you are a new user, then you can order 10 pieces PCBs, costing only $2. To place your order click on “Save to Cart”  button. Confirm your shipping address and shipping method.


Steps to Order SMT PCBs From JLCPCB - 

To order your SMT PCBs, visit JLCPCB (https://jlcpcb.com/RTA)

1.	 Drag and drop SMT PCBs file on site.
2.	 Choose your PCBs color and quantity.
3.	 To free SMT assembly for your PCB click on “SMT Assembly” button and then confirm.
4.	 Add your BOM file and CPL file.
5.	 Place your order click on “Save to Cart” button.
6.	 Confirm your shipping address and shipping method.
7.	 Pay your payment
8.	 Wait for confirmation mail.
9.	 For SMT Service, Click here (https://cart.jlcpcb.com/quote)
 
 
 Shipping and Billing - 
	
JLCPCB supported all shipping method can be seen below.

Estimated Delivery Time



•	DHL International Express 3-5 business days
•	UPS Worldwide Saver 3-6 business days
•	S.F Express (Standard) 5-8 business days
•	S.F Express (Economy) 8-15 business days
•	Singapore EMS 8-15 business days
•	Post Link Registered Mail 15-20 business days
•	ePacket 15-25 business days
•	Registered Air Mail 15-20 business days


JLCPCB supported Payment method.
•	PayPal
•	Credit/Debit Care
•	Prepaid wire transfer




Confirm PCBs Order - 

To confirm your order, pay your payment. Then accept PayPal, Credit/Debit Card, and Prepaid Wire Transfer. 
To manufacture your PCBs, it’ll take about 2 days. DHL will be fastest shipping method to arrive your ordered PCBs at your location.

All PCBs were well packed and quality was really good.
Thanks to JLCPCB for best quality PCBs.
