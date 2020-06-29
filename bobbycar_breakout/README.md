# hoverboard-breakout

Breakout board for hoverboard mainboards, it grands easy access to the boards uart, analog inputs PA2 and PA3 as well as I2C. It features a footprint for a generic 3.3V or 5V LDO (e.g. CJ78L05, L78L33ACUTR), 
screw terminals for the analog inputs, a power LED and a footprint for a nunchuck. 

Always mount the diode, the LED and the LDO. For I2C also two 3k3 pullups (labeled I2C) are mounted, for ADC you can add up to two pulldowns and filter capacitors.

The breakout board allows to connect two hoverboard mainbords. This can be done either to use them in parallel (e.g. route ADC to both) or to connect the two mainboards via UART. To connect the hoverboard mainboards in parallel, connect the middle pad of JP1 to the lower pad and the middle pad of JP2 to the upper pad. To connect the hoverboard mainboards via UART solder the pads of JP1 and JP2 the other way round.

![Jumper settings](/bobbycar_breakout/jumper.jpeg)

Some of the resistors and capacitors can either be mounted with wired components or with smd components.

![Frontview](/bobbycar_breakout/bobbycar.png)
![Plug1](/bobbycar_breakout/plug1.jpeg)
![Plug2](/bobbycar_breakout/plug2.jpeg)
