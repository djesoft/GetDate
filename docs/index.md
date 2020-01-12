---
layout: default
---

## Usage

**GetDate** [DT1] [DT2] ... [DTn] [pause]

[DT1] [DT2] are date and time information from a file.

This format is usually dd/mm/yyyy hh:mm

Since this contains a space do make sure to enclose the date/time between double quotes

[pause] waits for a key press after output displayed before continuing. This has to be the last parameter.

For each date/time paremeter a value is output giving the number of minutes between 01/01/2000 00:00 and the given date/time.

If a date/time parameter is invalid it will be skipped.

After all values are output the number of valid date/time parameters is output too.





## EXAMPLE

`GetDate "06/06/2012 18:52" "24/06/2012 11:27"`

`6538732 6564207 2`

