# [animated-winner](https://github.com/shaakha/animated-winner)

This script will help you interactively search within and edit a pcap file. Check sample command files for more details.

## Usage:

```bash
python aw.py
animated-winner - An Interactive Pcap Editor
>>>
$
$ python aw.py <cmds.search.txt
animated-winner - An Interactive Pcap Editor

Nothing to search! Use 'analyze' first.

Read 43 packets from http.cap

search for tcp packets
Found 41 matches for search query '6 in ip.proto': 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 14, 15, 16, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43

search for udp packets
Found 2 matches for search query '17 in ip.proto': 13, 17

search for raw string
Found 5 matches for search query '(?i)Google in pay.load': 8, 10, 18, 26, 36

search for raw string
Incorrect searchvalue 'test' for protofield 'dns.ns', expected <type 'int'>

search for raw string
Found 19 matches for search query '.* in pay.load': 4, 6, 8, 10, 11, 14, 16, 18, 20, 21, 23, 26, 27, 29, 31, 32, 34, 36, 38

search within ether packets
Found 20 matches for search query '00:00:01:00:00:00 in ether.src': 1, 3, 4, 7, 9, 12, 13, 15, 18, 19, 22, 25, 28, 30, 33, 35, 37, 39, 41, 42
$```

## Credits:

* [PcapEdit](https://github.com/7h3rAm/pcapedit)
* [Scapy](https://github.com/secdev/scapy)
