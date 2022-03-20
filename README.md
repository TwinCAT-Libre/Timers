# Timers
Timing based function blocks

## Function Blocks
### fb_BaseTimer
Base class which all timers are extended from


### fb_Heartbeat
Generates a periodic boolean signal for monitoring from another source (ADS, PLC, etc)
![Heartbeat](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/Heartbeat.jpg)

### fb_TOF
Off delay timer with additional information
![TOF](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TOF.jpg)

### fb_TOFRT
Off delay retentive reset timer with additional information
![TOFRT](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TOFRT.jpg)

### fb_TON
Off delay timer with additional information
![TON](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TON.jpg)

### fb_TONRT
On delay retentive reset timer with additional information
![TONRT](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TONR.jpg)

### fb_Watchdog
Monitors a boolean signal, and sets output TRUE if no change (rising or falling edge) has occured in a specified time
![Watchdog](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/Watchdog.jpg)

## Functions
None

## DUTs
None
