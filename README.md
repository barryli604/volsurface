# volsurface
Useless volatility surface webapp

## Getting Started
assuming you are using `conda`:
```
conda activate
pip install -r requirements.txt
```

## Features
### Get Volatility Surface for any stock
```python
def get_opt_chain_vol(ticker, is_call = True):
  ''' return a list of json object containing the implied volatility for each
  traded option found
  Args:
    ticker: underlying stock's ticker
    is_call: return calls' vol data, else return puts' vol data
  '''
  pass
```

example output of the function `get_opt_chain_vol()`:
```
[
  {'expiry': 2021-07-23, 'strike': 100, 'implied_volatility': 0.37, 'type': 'call'},
  ...
]
```
