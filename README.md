

# <img src="libradefi.png" height="120px">

**Libra Defi smart contract development.** 


## Overview

### Installation

```console
$ npm install @libradefi/contracts
```

libradefi Contracts features a [stable API], which means your contracts won't break unexpectedly when upgrading to a newer minor version.

### Usage

Once installed, you can use the contracts in the library by importing them:

```solidity
pragma solidity ^0.8.0;

import "@libradefi/contracts/token/TRC20/TRC20.sol";

contract MyCollectible is TRC20 {
    constructor() TRC20("MyCollectible", "MCO") {
    }
}
```

_If you're new to smart contract development, head to [Developing Smart Contracts] to learn about creating a new project and compiling your contracts._


## Contribute

libradefi exists thanks to its contributors. There are many ways you can participate and help build high quality software.
## License

libradefi is released under the [MIT License](LICENSE).
