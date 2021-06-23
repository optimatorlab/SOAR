Facility data may be imported with the following Python code:

```
import json
import urllib.request

with urllib.request.urlopen("https://raw.githubusercontent.com/optimatorlab/SOAR/master/data/soar.json") as url:
    soar_data = json.loads(url.read().decode())

soar_data
```

A Jupyter notebook is available at [SOAR_data.ipynb](SOAR_data.ipynb)
