
## Why we need communication model?

- Agnostic applications
    - We have many different n/w mediums, if we don't have a standard model, application would have to know about which medium is being used
    - Maybe, separate application for different n/w medium

- N/w Equipment management
- Decoupled innovation
    - Innovations on a layer without affecting other layers

## OSI (Open systems interconnection) model

7 layers, each describes a specific networking component

- Layer 7 - Application - HTTP/FTP/gRPC
- Layer 6 - Presentation - Encoding, Serialization
- Layer 5 - Session - Connection establishment, TLS
- Layer 4 - Transport - TCP/UDP
- Layer 3 - Network - IP
- Layer 2 - Data link - Frames, Mac address, Ethernet
- Layer 1 - Physical - Electric signals, fibre or radio waves

## Shortcoming of OSI

- Many layers, hard to comprehend
- Hard to comprehend uses of each layer
- Easier to deal with 7-6-5 as one single application layer
- TCP/IP model does that

## TCP/IP

- Simpler than OSI, with only 4 layers
- Application (5,6,7)
- Transport (4)
- Internet (3)
- Data link (2)
- Physical layer is not officially covered in this model