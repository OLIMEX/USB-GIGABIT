# USB-GIGABIT
USB 1.1, USB 2.0, USB 3.0 to Ethernet 10/100/1000Mbit converter

With A20 OLinuXino boards and USB 2.0 host the speed is: upload 319 Mbit, download 295 Mbit.


## Commands
    iperf3 -c 192.168.0.xxx -p 2001 -t 3
    iperf3 -c 192.168.0.xxx -p 2001 -t 3 -R
    


## Results

| Board     |     Upload    |    Download   |
| ----------|--------------:|--------------:|
| PC        | 231 Mbits/sec | 312 Mbits/sec |
| A20-MICRO | 319 Mbits/sec | 295 Mbits/sec |


# License
- Hardware is with CERN OHL v1.2 license
- Documentation is with CC BY-SA 4.0 license
