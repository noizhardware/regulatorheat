# REGULATOR HEAT
## Calculates heatsink ratings and temperatures for voltage regulators
### in OpenOffice .ODS spreadsheet format AND equations in .TXT format

In this file I've put some useful calculations to design your power supply, based on the attached design, you can change the regulators of course, update the specs if you do so.

The equations take into account a full-wave diode rectifier, and assume an AC frequency of 50Hz, to calculate the worst case heat. (with 60Hz AC the temperatures might be slighly lower, but better be on the safe side)

The "MAX current absorption" field calculates it using old inserted data without feedback, so it's not super accurate, but gives you a ballpark.
I recommend you always update the current absorption with your readings.
