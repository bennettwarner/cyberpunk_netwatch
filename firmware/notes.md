avrdude.exe -c USBasp -p m328p -U lfuse:r:-:i -v
avrdude.exe -c USBasp -p m328p -U lfuse:w:0xE2:m
avrdude.exe -c USBasp -p m328p -U hfuse:w:0xDA:m
avrdude.exe -c USBasp -p m328p -U efuse:w:0xff:m
avrdude.exe -c USBasp -p m328p -U lfuse:r:-:i -v
avrdude.exe -c USBasp -p m328p