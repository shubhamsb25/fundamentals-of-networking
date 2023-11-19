
## Host to host communication?
- If we have millions of devices, how to communicate with other devices, a broadcast would be too costly
- If we use mac address, we won't know where the other device is, we would have to scan the whole n/w to find out the destination device
- Address need to get better
- We need routability, need the IP address

## Host to host communication, how?
- IP has two parts
- One part to identify n/w and other for host
- Use n/w part to eliminate non interesting n/ws
- Use host part to identify host
- But we still need MAC address (why?, coz on low level, we need to exactly pin point which device)

## A host can have many apps running?
- It's not enough to find out host
- Host is runnig many different apps, so we need ports
- we can send http request on port 80, dns on port 53, ssh on port 22, all running on same server

