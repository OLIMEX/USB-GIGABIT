# USB-GIGABIT
USB 1.1, USB 2.0, USB 3.0 to Ethernet 10/100/1000Mbit converter

Transfer troughput is up to 950Mbits/s when connected to USB 3.0 ports and GbE network.

Using the A20 OLinuXino boards and USB 2.0 host the speed is: upload 319 Mbit, download 295 Mbit.


## Commands
    iperf3 -c 192.168.0.xxx -p 2001 -t 3
    iperf3 -c 192.168.0.xxx -p 2001 -t 3 -R
    
## Empirical Test Results

Using the commands listed above and good grade Gigabit equipment.

| Board      |     Upload    |    Download   |
|------------|---------------|---------------|
| PC USB 3.0 | 933 Mbits/sec | 942 Mbits/sec |
| PC USB 2.0 | 290 Mbits/sec | 312 Mbits/sec |
| A20-MICRO  | 319 Mbits/sec | 295 Mbits/sec |


# License
- Hardware is released under CERN OHL v1.2 license
- Documentation is released under CC BY-SA 4.0 license
