# pyndodax
Python wrapper for indodax.com API

compatible with Python 3

```python
import indodax
```

Public API:
```python
indodax.getTicker()
indodax.getDepth()
indodax.getTradeHistory()
```

Trade API:
```python
key = "API key"
secret = "Secret key"

account = indodax.TradeAPI(key, secret)

account.getInfo()
account.transHistory()
account.trade()
account.tradeHistory()
account.openOrders()
account.orderHistory()
account.getOrder()
account.cancelOrder()
```
