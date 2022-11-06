# Currency Data Process Library
A small demo library for MGGY-8411 Data Engineering B, NYU Tandon.

### Installation
```
pip install DE-FOREX-Library
```

### Get started
How to get currency real-time conversion data:

```Python
from polygon_data import data_process_helper

# Instantiate a data process helper object
dp_helper = data_process_helper()

# Call the collect_data method
dp_helper.collect_data(currency_pairs)