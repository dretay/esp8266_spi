

1. HiZ
2. 1-WIRE
3. UART
4. I2C
5. SPI
6. 2WIRE
7. 3WIRE
8. LCD
x. exit(without change)

(1)>5
Set speed:
 1. 30KHz
 2. 125KHz
 3. 250KHz
 4. 1MHz

(1)>3
Clock polarity:
 1. Idle low *default
 2. Idle high

(1)>1
Output clock edge:
 1. Idle to active
 2. Active to idle *default

(2)>
Input sample phase:
 1. Middle *default
 2. End

(1)>
CS:
 1. CS
 2. /CS *default

(2)>
Select output type:
 1. Open drain (H=Hi-Z, L=GND)
 2. Normal (H=3.3V, L=GND)

(1)>2


SPI>[0x00 0x02 0xaa 0xaa 0xad 0xbb 0xbb 0xbb]
