# nethereum-sandbox
Samples and experiments with [Nethereum](https://nethereum.com/).


Initial repo based on [Get Started with Nethereum](https://docs.nethereum.com/en/latest/getting-started/).
It just displays the balance of the [Ethereum Foundation account](https://etherscan.io/address/0xde0b295669a9fd93d5f28d9ec85e40f4cb697bae) on mainnet.

A similar example can also be found at the [Nethereum Playground](http://playground.nethereum.com/csharp/id/1001).

Requires dotnet CLI.

**NB**: You will need to change the URL to use your own [Infura](https://infura.io/) API KEY. Otherwise you will received a 403 (Forbidden) exception.


Compile:

`dotnet build`

Run:

`dotnet run`
