## GiggleNote

### About GiggleNote

GiggleNote is a CryptoNote-based currency for learning about cryptocurrencies and enabling the comedy economy. Users of GiggleNote are encouraged to spend them frivolously on anything that makes you laugh. Trade with friends for anything funny, and especially on dark humor!

* Mineable using the CryptoNote algorithm
* Based on the CryptoNote reference implementation
* 3 minute block target
* Attempts to match the Bitcoin emission rate

It is not expected that GiggleNote will see large mining efforts, and will be viably mined on CPUs for anyone to participate and learn. GiggleNote is intended to be half-joking, and likely will not ever acheive significant value, making it fun and easy to jump in and share with friends. 

GiggleNote is backed by something of value! I will tell you a joke in exchange for some GiggleNotes. There is no official pegged rate, but I will expect at least 1 GiggleNote for a joke. Users of GiggleNote are encouraged, but not required, to offer a similar "backing".

### Roadmap

* Fork and build GUI wallet
* Mining pool?

### Building From Source

#### Ubuntu

`sudo apt-get update && sudo apt-get install -y build-essential libboost-all-dev cmake gcc git`

`git clone https://github.com/jbisterfeldt/GiggleNote.git`

`cd GiggleNote`

`make` or alternately, `make j#` where # is number of threads to use

Binaries will be available in GiggleNote/build/release/

Run `gigglewalletd`, create a wallet and record your address (found with `address` in gigglewalletd, then `giggled` and `giggleminer`. 

#### Windows

TODO

### Precompiled Binaries

TODO - Ubuntu 14.04 and 16.04 binaries will be available shortly