# HifiviRev1B-BareMetal-SPI
 BareMetalSPI master for the Sifi HiFive rev1B board
 
 
 to initialize the SPI use the void SPIinit(int baudspeed) function
 
 SPISend(data) will send 1 packet and also read the FIFO out of the spi recieve.
 SPISendAndReadValue(data) can be used to send an commando so the slave has time to put the right chosen value in their FIFO and then read it back out by the master by sending an other packet
