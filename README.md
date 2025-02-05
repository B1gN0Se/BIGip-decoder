# BIGip-decoder

Detecting and decoding BIG IP cookies in bash

Bash script to print out private IPs, ports and other stuff from F5's BIG IP Loadbalancers -- from not encrypted cookies which is still the default. It detects all cookies, also the AES encrypted ones.

**Usage**

``decoder.sh <URL>`` or ``decoder.sh <cookie value>`` or ``decoder.sh <cookie name=cookie value>``

**Example**

``decoder.sh TEST`` gives you an idea by running it against a predefined header
