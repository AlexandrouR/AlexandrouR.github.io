web3j
=====

web3j is a highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network:

![image](https://docs.web3j.io/_images/web3j_network.png)

This allows you to work with the [Ethereum](https://www.ethereum.org/) blockchain, without the additional overhead of having to write your own integration code for the platform.

The [Java and the Blockchain](https://www.youtube.com/watch?v=ea3miXs_P6Y) talk provides an overview of blockchain, Ethereum and web3j.

Features
========

-   Complete implementation of Ethereum\'s [JSON-RPC](https://github.com/ethereum/wiki/wiki/JSON-RPC) client API over HTTP and IPC
-   Ethereum wallet support
-   Auto-generation of Java smart contract wrappers to create, deploy, transact with and call smart contracts from native Java code ([Solidity](http://solidity.readthedocs.io/en/latest/using-the-compiler.html#using-the-commandline-compiler) and [Truffle](https://github.com/trufflesuite/truffle-contract-schema) definition formats supported)
-   Reactive-functional API for working with filters
-   [Ethereum Name Service (ENS)](https://ens.domains/) support
-   Support for Parity\'s [Personal](https://github.com/paritytech/parity/wiki/JSONRPC-personal-module), and Geth\'s [Personal](https://github.com/ethereum/go-ethereum/wiki/Management-APIs#personal) client APIs
-   Support for [Infura](https://infura.io/), so you don\'t have to run an Ethereum client yourself
-   Support for ERC20 and ERC721 token standards
-   Comprehensive integration tests demonstrating a number of the above scenarios
-   Command line tools
-   Android compatible
-   Support for JP Morgan\'s Quorum via
    [web3j-quorum](https://github.com/web3j/quorum)

Dependencies
============

It has five runtime dependencies:

-   [RxJava](https://github.com/ReactiveX/RxJava) for its reactive-functional API
-   [OKHttp](https://hc.apache.org/httpcomponents-client-ga/index.html) for HTTP connections
-   [Jackson Core](https://github.com/FasterXML/jackson-core) for fast JSON serialisation/deserialisation
-   [Bouncy Castle](https://www.bouncycastle.org/) ([Spongy Castle](https://rtyley.github.io/spongycastle/) on Android) for crypto
-   [Jnr-unixsocket](https://github.com/jnr/jnr-unixsocket) for \*nix IPC (not available on Android)

It also uses [JavaPoet](https://github.com/square/javapoet) for generating smart contract wrappers

Donate
======

You can help fund the development of web3j by donating to the following wallet addresses:

---------- --------------------------------------------
  Ethereum   0x2dfBf35bb7c3c0A466A6C48BEBf3eF7576d3C420

  Bitcoin    1DfUeRWUy4VjekPmmZUNqCjcJBMwsyp61G
---------- --------------------------------------------

Commercial support and training
===============================

Commercial support and training is available from [web3labs](https://www.web3labs.com/).

