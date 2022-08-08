# test.pcap
Sniffed the data one from https://support.apple.com and another from https://www.apple.com
By command `sudo tcpdump -i eth0 -w test.pcap`

# ja3_output.json
Get from ja3.py with command `ja3 --json test.pcap > ja3_output.json`

# ja3s output
Get it from `python python/ja3s.py --json test.pcap > ja3s_output.json`