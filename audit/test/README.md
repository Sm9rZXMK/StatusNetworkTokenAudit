# Status Network Token - Testing

## Requirements

* The tests works on OS/X. Should work in Linux. May work in Windows with Cygwin
* Geth/v1.6.0-stable-facc47cb/darwin-amd64/go1.8.1
* Solc 0.4.9+commit.364da425.Darwin.appleclang

<br />

<hr />

## Executing The Tests

* Run `geth` in dev mode

      ./00_runGeth.sh

* Run the test in [01_test1.sh](01_test1.sh)

      ./01_test1.sh

* See  [test1results.txt](test1results.txt) for the results and [test1output.txt](test1output.txt) for the full output.

<br />

<hr />

## Note

I prefer to test the Ethereum smart contracts against the Mainnet clients, using a Dev blockchain. This is to reduce the effects of different behaviours when testing agains truffle or one of the other testing frameworks.