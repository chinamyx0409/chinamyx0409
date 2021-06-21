- 👋 Hi, I’m @chinamyx0409
- 👀 I’m interested in python sql, data engineering
- 📫 How to reach me chinamyx0409@gmail.com

import pandas as pd

from datetime import date

df = pd.DataFrame({'Date':pd.date_range(start="2021-01-01",end="2021-01-03"), 'Rate':[0.1,0.12,0.13],'Price':[20,20.5,30.5],'Code':['AAPL','GOOG','CITI']})

[df.loc[:,x] for x in df]

<!---
chinamyx0409/chinamyx0409 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
