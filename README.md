# awesome-huff
A curated list of resources for Huff language.

```
                          ,....,
                        ,::::::<
                      ,::/^\"``.
                      ,::/, `   e`.
                     ,::; |        '.
                     ,::|  \___,-.  c)
                    ;::|     \   '-'
                    ;::|      \
                    ;::|   _.=`\
                     `;:|.=` _.=`\
                      '|_.=`   __\
                       `\_..==`` /
                        .'.___.-'.
                       /          \
                     ('--......--')
                      /'--......--'\
                     `"--......--"`

        _____ _ _ _ _____  ___  ___  ____  _____
        (____ | | | | ___ |/___)/ _ \|    \| ____)
        / ___ | | | | ____|___ | |_| | | | | ____|
        \_____|\___/|_____|___/ \___/|_|_|_|_____)

                 _              ___    ___
                | |            / __)  / __)
                | |__  _   _ _| |__ _| |__
                |  _ \| | | (_   __|_   __)
                | | | | |_| | | |    | |
                |_| |_|____/  |_|    |_|

```

# 18-Jul-22 -- HUFF-DOCS is now **LIVE**! -- Start with the official docs for setup, usage, and tutorials at [https://docs.huff.sh/](https://docs.huff.sh/)

## What the heck is Huff?

Huff is a low-level programming language designed for developing highly optimized smart contracts that run on the Ethereum Virtual Machine (EVM). Huff does not hide the inner workings of the EVM. Instead, Huff exposes its programming stack and provides useful tools like constants and macros.

Initially developed by the [Aztec Protocol](https://github.com/AztecProtocol) team, Huff was created to write [Weierstrudel](https://github.com/AztecProtocol/weierstrudel), an on-chain elliptical curve arithmetic library that requires incredibly optimized code which neither Solidity nor Yul could provide. [Huff](https://github.com/huff-language/huffc) was later rewritten by [Jet Jadeja](https://twitter.com/JetJadeja) in Typescript, and finally [it has been rewritten in Rust](https://github.com/huff-language/huff-rs) as `huff-rs` which is the version we use today.

Huff can be used to write highly-efficient smart contracts for use in production, or it can serve as a way for beginners to learn more about the EVM.

## Join the movement on Twitter
 - Follow [@huff_language](https://twitter.com/huff_language) to keep up with the latest news and announcements -- turn those notifications on, anon!
 - Follow [the Aztec Protocol team](https://twitter.com/aztecnetwork), the original creators of Huff.
 - Follow [Jet Jadeja](https://twitter.com/JetJadeja) The young prince of the Huff empire, aka "Sensei".
 - And a few other Huff chads: [@asnared](https://twitter.com/asnared), [@big_tech_sux](https://twitter.com/big_tech_sux), [@d1ll0nk](https://twitter.com/d1ll0nk), [@exp_table](https://twitter.com/exp_table), [@jtriley](https://twitter.com/jtriley_eth), [@merkleplant_eth](https://twitter.com/merkleplant_eth), [@sw0nt](https://twitter.com/sw0nt), [@vex_0x](https://twitter.com/vex_0x)

## Drop a gm in the Discord
 - Huff is still young, but it already has a thriving community. People on the [Huff discord](https://discord.gg/W5Cff3Kh) are helpful, friendly, and chill.

## Start Here
- [Huff landing page](https://huff.sh/) **NEW!** Sites up! The landing page for all things Huff. Here you can
 find links to [Github](https://github.com/huff-language), [Twitter](https://twitter.com/huff_language), and [huff-docs](https://docs.huff.sh/).
- [The Huff Docs](https://docs.huff.sh/) ➸ START HERE ➸ Here you'll find installation guides, reference, tutorials and everything you need to know about Huff. What are you waiting for, anon?

## Official huff-language Github repo
This is your main GH org for all things Huff: https://github.com/huff-language.
 - [huff-rs](https://github.com/huff-language/huff-rs) You'll be installing this, the new compiler built in Rust, developed by the community and recently released to the public.  After installing `huffc` it's time to start hacking! Write your first Huff function, anon. Start with something simple like adding two numbers.  See the tutorials in the docs.
 - [huff-project-template](https://github.com/huff-language/huff-project-template/) A template for bootstrapping new Huff projects. Includes Foundry `HuffDeployer`.
 - [vscode-huff](https://github.com/huff-language/vscode-huff) A VSCode extension for Huff with syntax highlighting.  Also available from within your VSCode in the Extensions Marketplace.
 - [hufflime](https://github.com/nguyenphuminh/hufflime) A Sublime Text package for Huff syntax highlighting.
 - [huff-examples](https://github.com/huff-language/huff-examples) Currently has wip versions of ERC20 and ERC721.
 - [huff-breakage](https://github.com/huff-language/huff-breakage) Incorrect, Breaking, and Footgunned Huff Contracts. You'll learn a lot about Huff by reading what not to do in this excellent resource by [@asnared](https://twitter.com/asnared).
 - [huff-debug](https://github.com/huff-language/huff-debug) An easy hevm debug integration for hardhat-huff projects.
 - [foundry-huff](https://github.com/huff-language/foundry-huff) Foundry support for Huff.  Includes HuffDeployer to compile and test Huff contracts.
 - [hardhat-huff](https://github.com/huff-language/hardhat-huff) Huff support for Hardhat.

## Huff articles
 - [Entering the Huff Ecosystem](https://merkleplant.xyz/posts/entering-the-huff-ecosystem) A deep dive into [TSOwnable-huff](https://github.com/byterocket/TSOwnabe-Huff) by the author, [@merkleplant_eth](https://twitter.com/merkleplant_eth).
 - [Huff vs Yul for EVM Smart Contracts](https://medium.com/@jtriley15/huff-vs-yul-for-evm-smart-contracts-620d1d618197) A well written and informative introduction to Huff by [@jtriley](https://twitter.com/jtriley_eth)
 - [From Zero to Nowhere](https://medium.com/aztec-protocol/from-zero-to-nowhere-smart-contract-programming-in-huff-1-2-ba2b6de7fa83) An informative, 4 part series and deep dive into Huff written by the [team that developed Huff](https://github.com/AztecProtocol).
 - [EVM Deep Dives: The Path to Shadowy Super](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy) A great series by [@noxx3xxon](https://twitter.com/noxx3xxon) with a very deep dive into the evm.

## Huff projects you can learn from and contribute to
 - [huff-clones](https://github.com/clabby/huff-clones) Rewrite of clones-with-immutable-args in Huff.
 - [TSOwnable-huff](https://github.com/byterocket/TSOwnabe-Huff) An Ownable Implementation using Two-Step Transfer Pattern written by [@merkleplant_eth](https://twitter.com/merkleplant_eth).
 - [Solmate ERC20](https://github.com/devtooligan/huffhuffpass/blob/main/src/ERC20.huff) The only ERC20 implemented on Huff fully complete with all functionality (includes EIP-2612 Permit) and passing all [Solmate](https://github.com/transmissions11/solmate) tests.
 - [huff-learning](https://github.com/manasbir/huff-learning/tree/main/contracts) Some math and other functions implemented in Huff.
 - [huff-tools](https://github.com/kadenzipfel/huff-tools) A WIP set of tools for use with the huff language. Contains useful SafeMath functions.
 - [8-bit-array](https://github.com/h00p30/8bitArray) An implementation of an array in huff. It can store up to 32 8-bit values in a single storage slot.
 - [proxies](https://github.com/wolflo/proxies.huff) A few Ethereum delegate-call proxies written in raw bytecode via Huff.
 - [huff-pg](https://github.com/AdvaithD/huff-pg) An ERC20 implementation with SafeMath.

 ## Know your roots, anon
  - [AztecProtocol/huff](https://github.com/AztecProtocol/huff#why-is-it-called-huff) - This is the original version of Huff, developed by the [Aztec Protocol](https://github.com/AztecProtocol) team.
  - [Weierstrudel](https://github.com/AztecProtocol/weierstrudel) This is the project that Huff was written for.  Good luck with that math, anon.
  - [Oliver](https://github.com/AztecProtocol/Oliver) An elliptic curve point multiplication on the Baby-JubJub curve also developed by the [Aztec Protocol](https://github.com/AztecProtocol) team.
  - [huffc](https://github.com/huff-language/huffc) The  [Jet Jadeja](https://twitter.com/JetJadeja) rewrite in Typescript that was deprecated on 4-Jul-2022.

## EVM Opcodes
 - [evm.codes WITH HUFF PLAYGROUND](https://evm-codes-6zqgbc9nl-smlxl.vercel.app/playground?unit=Wei&codeType=Huff) **check it out!** This is a fork of evm.codes with Huff language support in the playground. Prototype, practice, and learn Huff with real time feedback and interactive debugger.
 - [evm.codes](https://www.evm.codes/) The ultimate resource for evm opcodes.  The playground will soon have Huff support!
 - [evm-puzzles](https://github.com/fvictorio/evm-puzzles) 10 puzzles to get you thinking like an evm.
 - [more-evm-puzzles](https://github.com/daltyboy11/more-evm-puzzles) 10 more puzzles!

**ASCII art of knight used in title by Joan Stark (jgs)
