# ccxt.pro

* [Install](ccxt.pro.install)
* [User Manual](ccxt.pro.manual)
  * [Architecture Overview](ccxt.pro.manual#overview)
  * [Prerequisites](ccxt.pro.manual#prerequisites)
  * [Streaming Specifics](ccxt.pro.manual#streaming-specifics)
  * [Linking](ccxt.pro.manual#linking)
  * [Instantiation](ccxt.pro.manual#instantiation)
  * [Exchange Properties](ccxt.pro.manual#exchange-properties)
  * [Unified API](ccxt.pro.manual#unified-api)
    * [Public Methods](ccxt.pro.manual#public-methods)
      * [Market Data](ccxt.pro.manual#market-data)
        * [`watchOrderBook (symbol, limit, params)`](ccxt.pro.manual#watchOrderBook)
        * [`watchTicker (symbol, limit, params)`](ccxt.pro.manual#watchTicker)
        * [`watchTickers (symbols, params)`](ccxt.pro.manual#watchTickers) wip
        * [`watchOHLCV (symbol, timeframe, since, limit, params)`](ccxt.pro.manual#watchOHLCV)
        * [`watchTrades (symbol, since, limit, params)`](ccxt.pro.manual#watchTrades)
    * [Private Methods](ccxt.pro.manual#private-methods)
      * [Authentication](ccxt.pro.manual#authentication)
      * [Trading](ccxt.pro.manual#trading)
        * [`watchBalance (params)`](ccxt.pro.manual#watchBalance)
        * [`watchOrders (symbol, since, limit, params)`](ccxt.pro.manual#watchOrders) wip
        * [`watchCreateOrder (symbol, type, side, amount, price, params)`](ccxt.pro.manual#watchCreateOrder) wip
        * [`watchCancelOrder (id, symbol, params)`](ccxt.pro.manual#watchCancelOrder) wip
        * [`watchMyTrades (symbol, since, limit, params)`](https://github.com/ccxt-dev/ccxt/wiki/ccxt.pro/Manual#watchMyTrades) wip
      * [Funding](ccxt.pro.manual#funding) wip
        * [Deposit](https://github.com/ccxt/ccxt/wiki/Manual#deposit)
        * [Withdraw](https://github.com/ccxt/ccxt/wiki/Manual#withdraw)
        * [`watchTransactions (code, since, limit, params)`](https://github.com/ccxt/ccxt/wiki/Manual#watchTransactions)
* [Error Handling](ccxt.pro.manual#error-handling)
* [Troubleshooting](https://github.com/ccxt/ccxt/wiki/Manual#troubleshooting)
* [How To Submit An Issue](https://github.com/ccxt/ccxt/blob/master/CONTRIBUTING.md#how-to-submit-an-issue)
* [Usage Examples](https://github.com/ccxt/ccxt/tree/master/examples) wip
