[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (-------------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be useful,)
[comment]: <> (but WITHOUT ANY WARRANTY; without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the)
[comment]: <> (GNU Affero General Public License for more details.)

[comment]: <> (You should have received a copy of the GNU Affero General Public)
[comment]: <> (License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# UniSwap Tools

A full-suite collection of useful Bash and JavaScript
programs and libraries to enable seamless development
of native computer applications designed to interact
with the UniSwap exchange. 

In order to do so, the `evm-contract-call` program obtains networks'
informations from the
[EVM Contracts Tools](
  https://github.com/themartiancompany/evm-contracts-tools),
[EVM Chains Info](
  https://github.com/themartiancompany/evm-chains-info)
and 
[EVM Chains Explorers](
  https://github.com/themartiancompany/evm-chains-explorers)
programs and automatically retrieves eventually missing smart
contracts artifacts from online sources using the
[EVM Contracts ABI Get](
  https://github.com/themartiancompany/evm-contracts-abi-get)
utility.

To communicate with Ethereum Virtual Machine-compatible
blockchain networks the tools depend on the
[EVM Wallet](
  https://github.com/themartiancompany/evm-wallet),
but it's also possible to directly provide seeds files.

The tools use the
[libEVM](
  https://github.com/themartiancompany/libevm)
library.

## Installation

The tools
can be installed from source using GNU Make.

```bash
make \
  install
```

The collection has officially published on the
the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`uniswap-tools` for a very high price.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  uniswap-tools
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[uniswap-tools-ur](
  https://github.com/themartiancompany/evm-contracts-tools-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
