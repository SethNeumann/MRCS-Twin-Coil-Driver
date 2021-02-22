# REPO NAME: MRCS-Twin-Coil-Driver
## License: Creative Commons Attribution-NonCommercial-ShareAlike

Twin Coil Machines present some challenges:

    They tend to slam the points into the stock rails, eventually damaging the connection to the throwbar and the spikes or solder holding the stock rails down 
    can loosen or break.  They make a lot of electrical noise when the power is removed from the coils, which gets into other electronics, causing false operation.
    The coils will overheat and become damaged, if not catch fire, if current is applied for an extended period.
    
    In the past, Capacitive Discharge (CD) supplies were used to make an affordable supply that would protect the coil by not recharging while connected and limiting
    the constant current in case the controls failed and permanently energized the coil.

Our design drives both mild (Atlas, Bachmann, Lifelike, Peco) and "Nasty" PFM, Tenshodo, Ken Kidder, NJ International Twin Coil type machines.  The Twin Coil Driver
(TCD) shapes the pulses driving the switch machines to soften both the physical and electrical blow, reducing electrical noise and physical impact.  Pulse timing is
done in hardware (no chance of a software hang leaving power on).  The TCD works with CD power supplies and modern power supplies such as those used for LEDs, or
inexpensive bench supplies.  

The Twin Coil Driver has internal spike suppression diodes.  Input is logic level and the coils are fired on the rising and falling edge, so a simple toggle switch 
or logic level input controls the machine.
