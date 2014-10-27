Threat Research (Private)
=======================

Repository of threat research data. This repo is reserved for data that I've deemed sensitive, as I am yet to finish research and the threats are still active. Please email me for encryption passphrase. 

# Current Packages

The following are packages of threat intel data that have been released to date.

### October 27th, 2014

```
c3dfa10198dec42b8d947464c296d005  all_attempts.txt
386b84d658b2ffe31e14a41b9e5b2b55  all_ips.txt
e1648eb44af64e1c21b6aff1639dcc7c  logs_oct27_2014.tar.gz
caca8c09b820f8f8af7da0aff359b3e3  target_network_geo.txt
c0d24fc1ad8ad5d82891214152023234  target_networks.txt
667de6e1b695c922128f4f35f28ebbc3  targets.txt
854b0393706b038bc059527e75b82f2a  targets_sorted.txt
e7d6010f71b884b94fea1a4fa4d20c75  targets_unique.txt

$ wc *.txt
  443258   443260  5900717 all_attempts.txt
  443258   443258  6526522 all_ips.txt
     311     3763    32183 target_network_geo.txt
     311      311     3923 target_networks.txt
  523855   523855  7258822 targets.txt
    3170     6340    70373 targets_sorted.txt
    3170     3170    45013 targets_unique.txt
 1417333  1423957 19837553 total

all_attempts.txt	- This is a text file containing all username/password combinations attackers have attempted against my SSH honeypots. This file is unsorted and un-unique'd.
all_ips.txt		- This is a text file containing all IP addresses I've received SSH authentication attempts from. This file includes some benign IP addresses (such as mine) for testing, but is mostly malicious attackers or compromised boxes.
targets.txt		- This is a text file containing all IP addresses the "CHUILANG" group have targeted with Distributed Denial of Service (DDOS) attacks between September and October. This file is unsorted and uniqued.
logs_oct27_2014.tar.gz	- This is a tarball containing all of my raw kippo logs, including TTY logs of successful authentication attempts.
target_network_geo.txt	- This is a text file containing geo IP lookups of the different targets of the "CHUILANG" group. 
target_networks.txt	- This is a text file containing the class C's of all DDOS targets of the "CHUILANG" group. This is for geo lookup/whois purposes.
targets_unique.txt	- This is a text file containing a unique'd version of all DDOS targets of the "CHUILANG" group. Only one entry per IP.
targets_sorted.txt	- This is a text file containing a sorted version of all DDOS targets of teh "CHUILANG" group. IP address and number of occurences. 
```
