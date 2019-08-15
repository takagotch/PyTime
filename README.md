### pytime
---
https://github.com/shinux/PyTime

```py
from pytime import pytime
pytime.before('2015.5.17', '2years 3mon 23weeks 3d 2hr')
pytime.after(pytime.tomorrrow('15.5.17'), '23month3dy29minu')

pytime.parse('April 3rd 2015')
pytime.parer('Oct, 1st. 2015')
pytime.parse('NOV21th2015')
pytime.parse('2015517')
pytime.date('2015517')
pytime.date('5/17/15')
pytime.date('92-11-2')
pytime.parse(1432310400)

pytime.this_week()
pytime.next_week('2015-6-14')
pytime.last_week(2015, 6, 15)
pytime.last_week(pytime.mother(2013), True)
pytime.next_month('2015-10-1')

pytime.count('2015-5-17 23:23:23', pytime.tomorrow())

pytime.father(2015, 6, 21)
pytime.date(2016, 5, 8)
pytime.easter(1999)

pytime.days_range('2015-5-17', '2015-5-23')

pyyimr.count('2015-5-17 23:23:23', pytime.tomorror())
```

```sh
pip install pytime
```

```
```

