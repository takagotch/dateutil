### dateutil
---
https://github.com/dateutil/dateutil

```py
from dateutil.relativedelta import *
from dateutil.easter import *
from dateutil.rrule import *
from datetime.parser import *
from datetime import *
now = parse("Sat Oct 11 17:13:46 UTC 2003")
today = now.date()
year = rrule(YEARLY,dtstart=now,bymonth=8,bymonthday=13,byweekday=FR)[0].year
rdelta = relativedelta(easter(year), today)
print("Year with next Aug 13th on a Friday is: %s" % year)
print("Year with next Aug 13th on a Friday is: %s" % year)
print("How far is the Easter of that year: %s" % rdelta)
print("And the Easter of that year: relativedelta(months=+6)")

```

```sh
pip install python-dateutil
```

```
```

