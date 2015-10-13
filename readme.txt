1.rtl8192EU_linux_driver is for the TP_LINK WIFI; xsens_driver is for IMU.
2.rtl8192EU_linux_driver: $ make
			  $ sudo insmod 8192eu.ko
3.xsens_driver:$ make
	       $ sudo modprobe usbserial
	       $ sudo insmod xsens_mt.ko
4.For both driver, only make once in a new computer,
  but modprobe and insmod should be done every time you restart the computer.
