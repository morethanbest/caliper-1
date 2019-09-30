# Hyperledger Caliper

Welcome to the Hyperledger Caliper project. Caliper is a blockchain performance benchmark framework, which allows users to test different blockchain solutions with predefined use cases, and get a set of performance test results.

Currently supported blockchain solutions:
* [fabric v1.0+](https://github.com/hyperledger/fabric), the latest version that has been verified is v1.4.1
* [sawtooth 1.0+](https://github.com/hyperledger/sawtooth-core)
* [Iroha 1.0 beta-3](https://github.com/hyperledger/iroha)
* [Burrow 1.0](https://github.com/hyperledger/burrow)
* [FISCO BCOS v2.0.0](https://github.com/FISCO-BCOS/FISCO-BCOS)

[Hyperledger Composer](https://github.com/hyperledger/composer) is also supported.

Currently supported performance indicators:
* Success rate
* Transaction/Read throughput
* Transaction/Read latency(minimum, maximum, average, percentile)
* Resource consumption (CPU, Memory, Network IO,...)

See the [PSWG white paper](https://www.hyperledger.org/resources/publications/blockchain-performance-metrics) to find out the definitions and corresponding measurement methods.  

For more information on using Caliper please consult the [documentation site](https://hyperledger.github.io/caliper/)

## Install and usage
See the [related documentation page](https://hyperledger.github.io/caliper/vLatest/installing-caliper/).

## How to contact us

If you have any issues using Caliper that the documentation does not help you solve, please reach out to us through the following methods:
* [RocketChat](https://chat.hyperledger.org/channel/caliper) Please feel free to contact us on Rocket Chat (instant messaging). We monitor that channel as close as possible, but even if you don't have a problem that needs resolving, why not jump on and say hi ... we'd love to hear from you about your experiences and any new features you think we should work on.
* [Issues](https://github.com/hyperledger/caliper/issues) Feel free to raise an issue if you are facing a Caliper related problem

Caliper interacts with multiple blockchain technologies and consequently it *might* be an issue with the underlying blockchain technology being interacted with. You can seek specific help on these technologies within the following Rocket Chat channels:
* [Hyperledger Burrow](https://chat.hyperledger.org/channel/burrow)
* [Hyperledger Composer](https://chat.hyperledger.org/channel/composer)
* [Hyperledger Fabric](https://chat.hyperledger.org/channel/fabric)
* [Hyperledger Iroha](https://chat.hyperledger.org/channel/iroha)
* [Hyperledger Sawtooth](https://chat.hyperledger.org/channel/sawtooth)

## How to contribute

We welcome contributions to the Caliper code base. Please see [Contributing](/CONTRIBUTING.md) for more information.

## License
Hyperledger Project source code files are made available under the Apache License, Version 2.0 (Apache-2.0), located in the [LICENSE](LICENSE) file. Hyperledger Project documentation files are made available under the Creative Commons Attribution 4.0 International License (CC-BY-4.0), available at http://creativecommons.org/licenses/by/4.0/.
