# PC Hardware - Introduction 



Use assembler needs  knowledge of hardware (computer architecture).  

The fundamental blocks information of a computer are bits and bytes, this gives us a way to show to the computer instructions and data in the memory.


The main internal hardware components of the compute are:

- CPU

- Memory

- Records

  

### Bits and bytes

**Bits**

Bits are the smallest unit of the computers.

The bit can be magnetized(1, on) or not magnetized (0, off).

**Bytes**

Byte is a nine bits group, that gives us directions memory on disk and ram.

Each byte has eight bits to data and just one bit for parity (parity bit).

| Data | Data | Data | Data | Data | Data | Data | Parity |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |
| 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0      |

**Eight bits of data**

The eight bits of data allow to us represent characters like the letter 'A' or the symbol "*", but it just can let us show 255 different characters.

**Parity bite**

The parity bit is a bit that can verify if our data is fine.

The parity bit will be 1 if the count of the total data bits 1 are peers.

The parity bit will be 0 if the count of the total data bits 1 are not peers.



### Related bits

##### **Field**

A field is a group of bytes that represents a particular value.

- World are is a field with 2 bytes (16bits)

- Double world is a field with 4 bytes (32 bits)
- Quadruple world is a field with 8 bytes(64 bits)
- Paragraph is a field with 16 bytes (128 bits)
-  A Kilobyte(KB) are 1024 bits. 
- A Megabyte(MB) are 1048576 bits.