RAM = Random Access Memory
RAM is stored on the mother board in modules called DIMMs (Dual Inline Memory Module) 
	* it is  considered dual because it has 2 independent rows of these pins one on each side.

DIMM modules can have 168, 184, 240, or 288 pins

motherboard can have a various number of memory slots.  The average motherboard will have between 2 and 4 of them.

In order for data or program to run on a computer, it needs to be loaded into RAM first.

Data is stored into harddrive.  From harddrive it's stored into RAM and then the CPU can now access data and run the program.

If the memory is too low then it might not be able to hold all the data the CPU needs.  If this happens some of the data needs to be stored on the hd and then access the memory into the RAM.

To solve this problem you need to upgrade your RAM.

RAM requires constant electrical power to store data.  If power is loss then memory is erased.

DRAM = Dynamic RAM
	* Contains Capacitors.
		* capacitors hold bits of data.
		* capacitors have to be refreshed with electricity constantly. Otherwise they will forget the informtion they are holding.
		
SDRAM = Synchronous Dynamic RAM
	* Used today in RAM DIMMs
	* Also has capacitors
		* DRAM - operates Asynchronously with system clock.
			* means that it runs slower than system clock.
		* SDRAM - operates Synchronously with the system clock.
			* All signals are tied to the system clock for a better controlled timing.
			
DIIMs come in different memory sizes.
	* 128 MB to 32gb per DIMM.
	
64 04 32 bit data path refers to the number of bits of data that are transferred in 1 clock cycle.
	* the more bits that are transferred through a clock cycle then the faster the computer will be.  DIMMs have a 64 bit data path.  64 bits of data at a time.
	* SIMMs have a 32 bit datapath.
	* A single bit or 1 bit of data is the smallest form of data a computer can read. 
	* a computer only understands 1's and 0's.  
	* 1 byte = 8 bits so 64 bits can process 8 bytes at a time 64 divided by 8 equals 8.
	SDRAM is rated at different speeds.  An old SDRAM in the 90's could be labled pc-100 which operated at 100mhz.
	
PC-100 
	* 100 MHz = The speed at which it operates.
	* 8 byte wide bus.
		* 100 MHz X 8 bytes = 800 MB/s (800 megabytes per second)
		* In other words PC-100 RAM can transfer data at a maximum rate of 800 megabytes per second.
		
PC-133
	* 133 MHz
	* 8 byte wide bus
		* 133 MHz X 8 bytes = 1066 MB/s (1066 megabytes per second)
			* this actually equals 1064 but the 1066 is accurate because the actual clock speed is 133.3333.

RDRAM = RIMM
	* 184 pins 
	* looks similar to DIMMs
	* Debuted in 1999
	* Was a breakthrough in the speed of memory.
	* when it debuted in 1999 it ran at 800 MHz.
	* RDRAM only had a 2 byte wide bus.
	
DDR = Double Data Rate.
	* sends double the amount of data in each clock cycle. 
	* non DDR single data rate sends data on the rising edge of the clock cycle.
	* DDR sends data at rising (top) and falling (bottom) of clock cycle.
	* DDR RAM is labeled different.  DDR may include both the clock speed and the total bandwidth in it's name.
	* for example DDR-333 PC-2700 = 333 is clock speed 2700 is actual bandwidth.
	
DDR2 = Double Data Rate 2.
*  is faster than DDR because it allows for higher bus speeds and effectively sends twice the amount of data than DDR.
* it also uses less power.
* has 240 pins (compared to DDR which has 184 pins).
* DDR2 is labeled just like DDR with a small difference.
	* for example a DDR2 DIMM could be labeled DDR2-800 PC2-6400.
	* difference is the 2 right next to the DDR and the PC.
		
DDR3 = Double Data Rate 3
	* twice as fast as DDR2 and uses less power.
	* also has 240 pins.
	* bottom notches are in different places.
	* motherboards are made to accept a certain type of memory.  
	* an example o f DDR3 would be DDR3-1600 PC3-12800.

DDR4 = Double Data Rate 4.
	* 288 pins
	* less power than DDR3
	* offers higher range of speed.
	* DDR4-4266MHz PC4-34100 
		* 34100 megabytes per second.
In servers Memory Data Corruption cannot be tolerated.
* Financial, government, etc. Cannot go down.
* ecc = error correcting code
* non ecc DIMMs will have 8 chips.
* ecc DIMMs will have 9.
* most RAM modules are non ecc.
* ecc is mostly used in servers.  ecc memory is an extra precaution in regards to memory.

	
		
