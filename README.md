# Bitcoin Core Visual Studio Building Space
Repository for building Bitcoin Core on Visual Studio 2017 directly.

It's still wip (under refactoring) now. Use it at your own risk.

Original sourcecode of Bitcoin Core is [here](https://github.com/bitcoin/bitcoin).

## How to build
Open bitcoin-msvc.sln by [Visual Studio 2017](https://www.visualstudio.com/downloads/) and select build menu. That's all.

add '$(PlatformToolset)' == 'v142' in secp256k1-vc141.targets if use [Visual Studio 2017] compile.
