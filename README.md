Bleumintcoin Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/bleumintcoin-project/bleumintcoin.svg?branch=master)](https://travis-ci.org/bleumintcoin-project/bleumintcoin)

https://bleumintcoin.com

What is Bleumintcoin?
----------------

Bleu Mint Coin is a blockchain-based decentralized digital platform and a medium of exchange with its own cryptocurrency. 
BleuMintCoin uses its own independent block chain, and  it runs on its own infrastructure.
BleuMintCoin uses the fork of Litecoin, which has much faster block chain transaction history compared to Bitcoin. BleuMintCoin has a Proof of Work consensus protocol and its hashing algorithm called Scrypt at its core. 
Bleu, the color of both Sky and Sea, is a universally appealing color on the spectrum with non-polarizing traits. Colour bleu is associated with intelligence, knowledge, harmony, loyalty, confidence, depth or distance, infinity, and imagination. Our variant, Bleu, is a symbolic manifestation of all these traits.

Technical Rationale:
The aim of Bleu Mint coin is to provide a digital coin wallet to the public where they can invest and trade on their asset within a decentralized blockchain. 

Bleu Mint Coin will build and set up mining pools for our partners and enable them to get better Hashrate to mine our coins using High Spec VPS or Cloud Servers. Bleu Mint’s mining pool partners called Mining Hubs will use servers with an ultrafast configuration (CPU Mining), which in turn have a set of miners under them. Miners will get their block rewards for validating and putting up a block chain and mining hubs will further collect their transactions fees from the miners. 
Bleu Tokens (BleuT) to be launched very soon, BleuT will run on Solana Blockchain which is on “Proof of History Consensus. BleuT will be used as a gas fee for all products that are in the company’s road map. 

Application Rationale:
Bleu Mint Coin is owned by a Software house, Dynamic Solutions – DSAT Global with wide-ranging applications for the Supply Chain and e-commerce domain. Bleu Mint coins will be used as gas fee for a subset of our products and services in:
●	eCommerce: Crypto currency shopping cart checkout plugin for Magento & WordPress
●	Vehicle Maintenance: Vehicle Ownership
●	Product Management: Preventing Counterfeit Products

Community Rationale:
The main purpose of mining this coin  to allocate 30% of the pre-mined coin to charity work done by our company’s founder through the initiative called “The Pie in the sky - Food 4 Everyone” initiative – "FEED IN NEED"  in order to support the needy with meals and address the grave issue of hunger in the most underdeveloped parts of the globe and to support UNDP goals.
Another 10% of the pre-mined coin will be allocated to help and support women empowerment projects and the last 10% for community upliftment.
Apart from this, a small portion of the proceeds will be allocated to support the staff who had been working in our multinational software company, operational in five countries. 
Who are we? 
We are a 20-year-old software company with an extensive footprint in development, implementation and support of software products across platforms for Logistics, Supply Chain and the eCommerce Industry. 
This endeavour will tap into our internal talent and expertise in software skills with additional know-how in hardware, server, VMware and cyber-security. 
Where are we heading in the Road Map?
Organizational roadmap:
With the experience and talent accrued in running a 20-year-old successful Software house, which has its own products (IP Owned) for Logistics, Supply Chain & eCommerce, we have been relentlessly pursuing to expand into community driven products.
We have over 16 IP Owned Products which is being Licensed, Implemented and Supported in Global market. We are present in 5 countries at this juncture and our future growth plans are targeted to expand our operations in 15 countries. We cater to clients in more than 20 countries and our team supports 10 languages.
Product Roadmap:
Currently, we are drawing up requirements to implement Blockchain for eCommerce, Vehicle Maintenance and Product Management products, as detailed in the application rationale section.


For more information, as well as an immediately useable, binary version of
the Bleumintcoin Core software, see [https://bleumintcoin.com](https://bleumintcoin.com).

License
-------

Bleumintcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bleumintcoin-project/bleumintcoin/tags) are created
regularly to indicate new official, stable release versions of Bleumintcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The developer [mailing list](https://groups.google.com/forum/#!forum/bleumintcoin-dev)
should be used to discuss complicated or controversial changes before working
on a patch set.

Developer IRC can be found on Freenode at #bleumintcoin-dev.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

We only accept translation fixes that are submitted through [Bitcoin Core's Transifex page](https://www.transifex.com/projects/p/bitcoin/).
Translations are converted to Bleumintcoin periodically.

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
