# This is how to use it
In the project directory, run these commands:
```
 npm install
 npm start
```
## Reducers
The reducers maintain state

## Middleware

### Thunk
The [redux-thunk](https://github.com/gaearon/redux-thunk) middleware component is used to incercept the asynchronous server calls from `web3.filter()` events.

###
The [redux-logger](https://www.npmjs.com/package/redux-logger) middleware component provides clean logging of state before, actions and state after for debugging.


## State Model
The state model represents on-chain data including `accounts` and transactions `transactions` and off-chain data like the list of `cryptos` or tokens that can be transfered and `transfer` details captured from the view.

## Actions
The application state is initialized by calling actions `getAllAccounts`, `getCryptos` and `fetchTransactions`.  For now, `fetchTransactions` initalizes the `web3.filter()` to listen for the latest transacations.
