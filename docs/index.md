---
layout: default
---

## Usage

For each date/time group a value is output giving the number of minutes between 01/01/2000 00:00 and the input date/time.
After all values are output the number of values is output too.
If a date/time group cannot be understood it will be skipped.\n\n USAGE\n
**GetDate** [DT1] [DT2] ... [DTn] [pause]
[DT1] [DT2] are date and time information from a file.
This format is usually dd/mm/yyyy hh:mm

Since this contains a space do make sure to enclose the date/time between double quotes

[pause] waits for a key press after output displayed before continuing. This has to be the last parameter.

## EXAMPLE

**GetDate** "06/06/2012 18:52" "24/06/2012 11:27"
6538732 6564207 2

Text can be **bold**, _italic_, or ~~strikethrough~~.
