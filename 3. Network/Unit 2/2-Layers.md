

# OSI Layers



Upper layers doesn't know about network of network addresses.

Bottom layers determine how to rebuild a data stream from a transmitting host to a destination host's application.

1. **Application** (Upper layer)

   File, print message, database sand application services.

   - Provides an user interface.

2. **Presentation** (Upper layer)

   Data encryption, compression, and translation services

   - Presents data
   - Handles processing such as encryption

3. **Session** (Upper layer)

   Dialog control

   - Keeps different applications' data separate

4. **Transport** (Lower layer)

   End-to-end connection

   - Provides reliable or unreliable delivery.
   - Performs error connection before retransmit.

5. **Network** (Lower layer)

   Routing

   - Provides logical addressing, which routers use for path determination.

6. **Data link** (Lower layer)

   Framing

   - Combines packets into bytes and bytes into frames.
   - Provides access to media using MAC address.
   - Performs error detection, no correction.

7. **Physical**  (Lower layer)

   Physical topology

   - Moves bits between devices
   - Specifies voltage, wire speed, and pin-out of cables.