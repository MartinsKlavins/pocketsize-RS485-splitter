# Pocketsize RS485 splitter
Pocketsize RS485 splitter for DMX512 signal. Created for everyday use with focus on problematic device isolation, connection for far placed devices, simple "Y" type splitting.

![logo](/pictures/dmxsplit1.jpg)

### Technical info
* It is active, have seperate power supply for each DMX output and input.
* Galvanic and optic isolation for each DMX output and input.
* MAX485, 6N137 and 74HC14 for signal pathway.

### Notes
* AC/DC and DC/DC converters are main advantage of this splitter. Power supply is created with 4 converters. First stage – 230V AC to 12V DC, second stage – multiple 12/05V DC/DC. There are variety of them, but I don’t suggest to use 05/05 (because they didn’t gave steady 5V output, atleast not for me). Didn’t helped capacitors and LDO (for example L4941BV) for stabilization. Any way, the are small-sized and great solution!
