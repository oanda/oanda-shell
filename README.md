OANDA API Shell
===============

A simple bash client to access the [OANDA API](https://github.com/oanda/apidocs)

This client only supports access to the sandbox environment.

Supported commands:

* accounts - get a list of accounts
* account - set active account
* trades - get a list of trades
* marketOrder new - create a new market order
* trade get - show trade information

* rate - show the current rate for a provided instrument

**Note**: At startup a username is required to access the list of accounts, etc. For information on how to create a test account see the [API documentation](http://developer.oanda.com/docs/v1/accounts/#create-a-test-account) page, or issue the following command in a terminal.

    curl -X POST "http://api-sandbox.oanda.com/v1/accounts"

Required dependencies:

* curl, sed, perl (for uri_escape... will be removed later)
