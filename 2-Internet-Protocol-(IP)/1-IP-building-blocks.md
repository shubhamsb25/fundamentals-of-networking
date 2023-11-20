
## IP address
- Layer 3 entity
- Can be assigned automatically or statically
- Has network and host portion
- 4 bytes in IPv4 - 32 bits

## Network-Host
- a.b.c.d/x, x is the number of bits which represent the n/w and remaining ones the host
- example - 192.168.254.0/24
- First 3 bytes are n/w, rest are for hosts
- Which means we can have 2^24(1,67,77,216) n/ws and each has 2^8(255) hosts
- Also called a subnet

## Subnet mask
- 192.168.254.0/24 is also called a subnet
- 255.255.255.0 is the subnet mask
- It is used to figure out if the ip is in same subnet or not
