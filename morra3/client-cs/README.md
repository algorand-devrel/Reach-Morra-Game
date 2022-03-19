# Morra with C#

Build the client Docker container by executing `./build.sh`, then run like so:

```sh
$ ./reach rpc-run ./csharp.sh

Warning! Using development RPC key: REACH_RPC_KEY=opensesame.
Warning! The current TLS certificate is only suitable for development purposes.
Verifying knowledge assertions
Verifying for generic connector
  Verifying when ALL participants are honest
  Verifying when NO participants are honest
Checked 153 theorems; No failures!

> app
> node --experimental-modules --unhandled-rejections=strict index.mjs

*** Warning! TLS verification disabled! ***
 This is highly insecure in Real Life applications and must
 only be permitted under controlled conditions (such as
 during development)...
Alice played 4
Alice guessed total of 8
Bob played 2
Bob guessed total of 6
Actual total fingers thrown: 6
----------------------------
Alice saw outcome Bob wins
Bob saw outcome Bob wins
Alice went from 10 to 4.974.
  Bob went from 10 to 14.99.

```
