OANDA API Shell
===============

A simple bash client to access the [OANDA API](https://github.com/oanda/apidocs)

Supported commands:

* accounts - get a list of accounts
* account - set active account
* trades - get a list of accounts
* rate - show the current rate for a provided instrument

**Note**: At startup a username is required to access the list of accounts, etc.  For that, you may be able to use "testusr" (until user registration is supported).

Required dependencies:

* curl, sed, perl (for uri_escape... will be removed later)
