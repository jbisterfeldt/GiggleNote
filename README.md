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
* HD wallet
* Mobile wallet?
* Mining pool?

### Building From Source

#### Ubuntu

`sudo apt-get update && sudo apt-get install -y build-essential libboost-all-dev cmake gcc git`

`git clone https://github.com/jbisterfeldt/GiggleNote.git`

`cd GiggleNote`

`make` or alternately, `make j#` where # is number of threads to use

Binaries will be available in `GiggleNote/build/release/src` cd <path> to make the magic happen.

Run `./GiggleWallet`, create a wallet and record your address, (found with `address` in gigglewalletd, then `./giggled` and `./giggleminer`. Run `chmod +x <filename>` for any execute permission errors. 

Example: `./giggleminer --address <youraddresshere> --log-level 5 --threads 2`

Set `--threads #` to the number of cpu threads you wish to commit to mining. Giggletoshi commits a single thread at around 30h/s.

See `help` in giggled for more about the state of the gigglechain and gigglepeers. Use `set_log <loglevel>` to dial output up or down. Log level 4 is pretty verbose.

#### Windows

TODO

### Precompiled Binaries

Ubuntu 14.04 and 16.04 [binaries are available](https://github.com/jbisterfeldt/GiggleNote/tree/master/binaries). Please see [issue #1](https://github.com/jbisterfeldt/GiggleNote/issues/1) if you are unable to mine on 14.04.
