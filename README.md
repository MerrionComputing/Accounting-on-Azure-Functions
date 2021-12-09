# Accounting-on-Azure-Functions

[![Join the chat at https://gitter.im/Accounting-on-Azure-Functions/community](https://badges.gitter.im/Accounting-on-Azure-Functions/community.svg)](https://gitter.im/Accounting-on-Azure-Functions/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

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
