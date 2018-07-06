### CHANGELOG
`2018.6.20` - WebSocket added Tickers,Restful added Market Tickers. Tickers：Subscribes and gets all current trading pairs.

`2018.6.29` -Huobi API Change Notification

  **Summary:** : API enhancements to support HB10 ETF purchase and redemption
 
  **Change Effective date:** July 2nd, 2018, 16:00 Beijing Time
 
  **Change Type:**

  REST API | Websocket API|
  --|--|
  New GET and POST API |New symbols for existing API |
  New Symbols for existing API |  |

  **What are the Impacts on you, and what you need to do?**
 
The changes mentioned above are backward compatible for all existing API users.  The New APIs enclosed will become available for all eligible API users, no extra application required.  
 
`2018.7.6`

  **Summary:** 
  - `/v1/order/orders/place` add new order types: `buy-limit-maker`,`sell-limit-maker`。
  - new API: provide open orders of a symbol for an account：`/v1/order/openOrders`。
  - new API:cancel a batch of orders with certain criteria：`/v1/order/openBatchCancel`。
  
  **Change Effective date:**  July 6nd, 2018, 16:00 Beijing Time
