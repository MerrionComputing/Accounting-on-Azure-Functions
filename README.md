# Accounting-on-Azure-Functions
A sample project to demonstrate various techniques of working with Azure functions in a real world example

This will build on the **[Event Sourcing on Azure Functions](https://github.com/MerrionComputing/EventsSourcing-on-Azure-Functions)** project to add a real world, multiple domain example that performs basic **Fund Accounting** functionality.

It is also a test bed for testing out ideas about architecture and code organisation in a serverless / FaaS environment.

## Domains

### Market

For instrument identifiers, prices, exchange rates, exchanges and so on that are information generally available on the market.

### Fund

For tracking the performance, holdings and fees of a typical fund.

### Investor

For tracking the individual investor's interactions with one or more funds.
