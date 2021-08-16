# Risq Smart Contracts

Below is a list of smart contracts that are deployed and utilized across Risq Protcol.

## Token Contracts

| Token                                                                             | Address                                    |
| --------------------------------------------------------------------------------- | ------------------------------------------ |
| [RISQ](https://www.bscscan.com/token/0x584bC13c7D411c00c01A62e8019472dE68768430)    | 0xD9B4806A672A8Da6666c9d9d4B3B30eF6311611d |



### Liquidity Providers

Liquidity providers deposit tokens into liquidity pools and receive write tokens which represent their share in their respective pool. 


| Token                                                                              | Address                                    |
| ---------------------------------------------------------------------------------- | ------------------------------------------ |
| [writeWBTC](https://www.bscscan.com/token/0x5D6e644eBeE654a78BeB1207F33ce79Ca475Fd4E) | 0x0x5D6e644eBeE654a78BeB1207F33ce79Ca475Fd4E |
| [writeBNB](https://www.bscscan.com/token/0x6249C0e395Ab75f047183B21d2755babBD795A6f)  | 0x6249C0e395Ab75f047183B21d2755babBD795A6f |
| [writeETH](https://www.bscscan.com/token/0x7095b510f402463df8db51de869629f7094487c2)  | 0x7095b510f402463df8db51de869629f7094487c2 |
| [writeBCH](https://www.bscscan.com/token/0x262ECE00f404D01e6824e345a36C7330d8BCe34e)  | 0x262ECE00f404D01e6824e345a36C7330d8BCe34e |
| [writeLTC](https://www.bscscan.com/token/0xDE6046fE176d3D84A71312e589d9c3C629e92768)  | 0xDE6046fE176d3D84A71312e589d9c3C629e92768 |
| [writePAXG](https://www.bscscan.com/token/0xC62A72186B25e5bC966b53Ee91415B4724ff52C7) | 0xC62A72186B25e5bC966b53Ee91415B4724ff52C7 |
| [writeCOMP](https://www.bscscan.com/token/0xfe477c25b5286cc2304987af7cd05274962cf593)  | 0xfe477c25b5286cc2304987af7cd05274962cf593 |
| [writeCAKE](https://www.bscscan.com/token/0xD6A2782a2f6229CBF258633EB71725E92D6A19d2)  | 0xD6A2782a2f6229CBF258633EB71725E92D6A19d2 |
| [writeUNI](https://www.bscscan.com/token/0xf0cc28dee2df4e3482a09809cf6F26A41Fa65e4d)  | 0xf0cc28dee2df4e3482a09809cf6F26A41Fa65e4d |
| [writeLINK](https://www.bscscan.com/token/0xf60c7Ed4954f5DfEfea116aE851A8D4DBB864541)  | 0xf60c7Ed4954f5DfEfea116aE851A8D4DBB864541 |
| [writeYFI](https://www.bscscan.com/token/0x9a1f6843fc4bbe923b35e1f55462aecee09fe2fe)  | 0x9a1f6843fc4bbe923b35e1f55462aecee09fe2fe |
| [writeAMZN](https://www.bscscan.com/token/0x3d0bA06e66DC6405D64Db542473fDDe6243147F3)  | 0x3d0bA06e66DC6405D64Db542473fDDe6243147F3 |
| [writeGOOGL](https://www.bscscan.com/token/0x27883d6d5A0FEf1Cf565928259BBe1deaa2CF715)  | 0x27883d6d5A0FEf1Cf565928259BBe1deaa2CF715 |
| [writeTSLA](https://www.bscscan.com/token/0x91313522182d5aFa7862012619fFedBf745c41F2)  | 0x91313522182d5aFa7862012619fFedBf745c41F2 |

### Options contracts

| Options Contract                                                                                 | Address                                    | Github                                                                                                               |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| [WBTC options contract](https://www.bscscan.com/address/0xE1ffBB1999a5AB58c3cd8343823CE8E87A53e656) | 0xE1ffBB1999a5AB58c3cd8343823CE8E87A53e656 | [WBTCOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/WBTCOptions.sol)   |
| [BNB options contract](https://www.bscscan.com/address/0x209Ee82429FD4e26251ed01771338C94fCbAF717)  | 0x209Ee82429FD4e26251ed01771338C94fCbAF717 | [BNBOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/BNBOptionsBSC.sol)     |
| [ETH options contract](https://www.bscscan.com/address/0x54fA24438370b5e7F64a1C78319d0c1048d14711) | 0x54fA24438370b5e7F64a1C78319d0c1048d14711 | [ETHOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/ETHOptions.sol)   |
| [BCH options contract](https://www.bscscan.com/address/0x6Ee22C3b113B299D6D831C065547aaA900e03c3D)  | 0x6Ee22C3b113B299D6D831C065547aaA900e03c3D | [BCHOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/BCHOptions.sol)     |
| [LTC options contract](https://www.bscscan.com/address/0x8009A019d83C9826788cbb9BC868d9065AC7088f) | 0x8009A019d83C9826788cbb9BC868d9065AC7088f | [LTCOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/LTCOptions.sol)   |
| [PAXG options contract](https://www.bscscan.com/address/0x1F4d8beaB9668Eeb41beF9Ad17A5389b0A09DC43)  | 0x1F4d8beaB9668Eeb41beF9Ad17A5389b0A09DC43 | [PAXGOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/PAXGOptions.sol)     |
| [COMP options contract](https://www.bscscan.com/address/0x9E7Fe8C954C48F4dd7B259D2781f3fDBb247DebF) | 0x9E7Fe8C954C48F4dd7B259D2781f3fDBb247DebF | [COMPOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/COMPOptions.sol)   |
| [CAKE options contract](https://www.bscscan.com/address/0xA26f309BB16349a2394561277eA6f190D8Ac56f6)  | 0xA26f309BB16349a2394561277eA6f190D8Ac56f6 | [CAKEOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/CakeOptions.sol)     |
| [UNI options contract](https://www.bscscan.com/address/0x502f641ad75a751F914f8e87fF6416874d06bd17) | 0x502f641ad75a751F914f8e87fF6416874d06bd17 | [UNIOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/UNIOptions.sol)   |
| [LINK options contract](https://www.bscscan.com/address/0xF65cbCc2eC6dbF623F7C9a37327c181F11B8CE48)  | 0xF65cbCc2eC6dbF623F7C9a37327c181F11B8CE48 | [LINKOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/LINKOptions.sol)     |
| [YFI options contract](https://www.bscscan.com/address/0x41f6a36094cE2B1Ae6711674E5C19234B232AEb3) | 0x41f6a36094cE2B1Ae6711674E5C19234B232AEb3 | [YFIOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/YFIOptions.sol)   |
| [AMZN options contract](https://www.bscscan.com/address/0xF2E1Cd501491DFc74a4B6c7291fd9436853b8948)  | 0xF2E1Cd501491DFc74a4B6c7291fd9436853b8948 | [AMZNOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/AMZNOptions.sol)     |
| [GOOGL options contract](https://www.bscscan.com/address/0xc2C6483B8E984D170d1DDB92C819bE1ABc7e37FF) | 0xc2C6483B8E984D170d1DDB92C819bE1ABc7e37FF | [GOOGLOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/GOOGLOptions.sol)   |
| [TSLA options contract](https://www.bscscan.com/address/0xc308E64037A7889bC8722201e34b047847Ea52bc)  | 0xc308E64037A7889bC8722201e34b047847Ea52bc | [TSLAOptions.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/Options/GOOGLOptions.sol)     |

### $RISQ Staking Contracts

Holders share in the protocols profits. 10,000 RISQ are needed to be staked in one of the Staking Contracts. 

| Token                                                                           | Address                                    |
| ------------------------------------------------------------------------------- | ------------------------------------------ |
| [rWBTC](https://www.bscscan.com/token/0xe70aA6fB68D134333C95E3739B62dE42Ee43743e)  | 0xe70aA6fB68D134333C95E3739B62dE42Ee43743e |
| [rBNB](https://www.bscscan.com/token/0xe562eF7f719F97f915a9F53F8C54dA6155CA4797) | 0xe562eF7f719F97f915a9F53F8C54dA6155CA4797 |
| [rETH](https://www.bscscan.com/token/0x32E1e4502AE8aB3d9AFdC71bf34419Ea2d7eA37F)  | 0x32E1e4502AE8aB3d9AFdC71bf34419Ea2d7eA37F |
| [rBCH](https://www.bscscan.com/token/0x548edf447C586F4F82Eb40BDd068b30482E0E150) | 0x548edf447C586F4F82Eb40BDd068b30482E0E150 |
| [rLTC](https://www.bscscan.com/token/0x53e834c347fb8282bdA20E2e70C8A82fb5E9837b)  | 0x53e834c347fb8282bdA20E2e70C8A82fb5E9837b |
| [rPAXG](https://www.bscscan.com/token/0x1f976B41D430bD8b841996A721e096573e3Ae21a) | 0x1f976B41D430bD8b841996A721e096573e3Ae21a |
| [rCOMP](https://www.bscscan.com/token/0x3da7aEF1B1F496c860887B3E612C96Ca78C29F66)  | 0x3da7aEF1B1F496c860887B3E612C96Ca78C29F66 |
| [rCAKE](https://www.bscscan.com/token/0x2F1e9Ca5C4bD1E3a4cB173B2C0949dBc18413409) | 0x2F1e9Ca5C4bD1E3a4cB173B2C0949dBc18413409 |
| [rUNI](https://www.bscscan.com/token/0x492e4Cc315caC3e11CcF469518D6B4e44A00908f)  | 0x492e4Cc315caC3e11CcF469518D6B4e44A00908f |
| [rLINK](https://www.bscscan.com/token/0x4536D016588290862D93D763ea9140D0Bb4c9900) | 0x4536D016588290862D93D763ea9140D0Bb4c9900 |
| [rYFI](https://www.bscscan.com/token/0xE19E8335fCc72fb36f53B999c0c049c002Ff637E)  | 0xE19E8335fCc72fb36f53B999c0c049c002Ff637E |
| [rAMZN](https://www.bscscan.com/token/0xB9352a3B81f13A70257C04bA2ffBD53605eB5C65) | 0xB9352a3B81f13A70257C04bA2ffBD53605eB5C65 |
| [rGOOGL](https://www.bscscan.com/token/0x3bbc14BEF3265dfaeCdd5d2Fe93fBbE311142a19)  | 0x3bbc14BEF3265dfaeCdd5d2Fe93fBbE311142a19 |
| [rTSLA](https://www.bscscan.com/token/0xAbC2C0A1b16045311916DeC7a3336d09D82929a6) | 0xAbC2C0A1b16045311916DeC7a3336d09D82929a6 |

| Staking lot contract                                                              | Address                                    | Github                                                                                                             |
| --------------------------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| [rWBTC](https://www.bscscan.com/token/0xe70aA6fB68D134333C95E3739B62dE42Ee43743e)  | 0xe70aA6fB68D134333C95E3739B62dE42Ee43743e | [StakingWBTC.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking) |
| [rBNB](https://www.bscscan.com/token/0xe562eF7f719F97f915a9F53F8C54dA6155CA4797) | 0xe562eF7f719F97f915a9F53F8C54dA6155CA4797 | [StakingBNB.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rETH](https://www.bscscan.com/token/0x32E1e4502AE8aB3d9AFdC71bf34419Ea2d7eA37F)  | 0x32E1e4502AE8aB3d9AFdC71bf34419Ea2d7eA37F | [StakingETH.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rBCH](https://www.bscscan.com/token/0x548edf447C586F4F82Eb40BDd068b30482E0E150) | 0x548edf447C586F4F82Eb40BDd068b30482E0E150 | [StakingBCH.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rLTC](https://www.bscscan.com/token/0x53e834c347fb8282bdA20E2e70C8A82fb5E9837b)  | 0x53e834c347fb8282bdA20E2e70C8A82fb5E9837b | [StakingLTC.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rPAXG](https://www.bscscan.com/token/0x1f976B41D430bD8b841996A721e096573e3Ae21a) | 0x1f976B41D430bD8b841996A721e096573e3Ae21a | [StakingPAXG.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rCOMP](https://www.bscscan.com/token/0x3da7aEF1B1F496c860887B3E612C96Ca78C29F66)  | 0x3da7aEF1B1F496c860887B3E612C96Ca78C29F66 | [StakingCOMP.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rCAKE](https://www.bscscan.com/token/0x2F1e9Ca5C4bD1E3a4cB173B2C0949dBc18413409) | 0x2F1e9Ca5C4bD1E3a4cB173B2C0949dBc18413409 | [StakingCAKE.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rUNI](https://www.bscscan.com/token/0x492e4Cc315caC3e11CcF469518D6B4e44A00908f)  | 0x492e4Cc315caC3e11CcF469518D6B4e44A00908f | [StakingUNI.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rLINK](https://www.bscscan.com/token/0x4536D016588290862D93D763ea9140D0Bb4c9900) | 0x4536D016588290862D93D763ea9140D0Bb4c9900 | [StakingLINK.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rYFI](https://www.bscscan.com/token/0xE19E8335fCc72fb36f53B999c0c049c002Ff637E)  | 0xE19E8335fCc72fb36f53B999c0c049c002Ff637E | [StakingYFI.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rAMZN](https://www.bscscan.com/token/0xB9352a3B81f13A70257C04bA2ffBD53605eB5C65) | 0xB9352a3B81f13A70257C04bA2ffBD53605eB5C65 | [StakingAMZN.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rGOOGL](https://www.bscscan.com/token/0x3bbc14BEF3265dfaeCdd5d2Fe93fBbE311142a19)  | 0x3bbc14BEF3265dfaeCdd5d2Fe93fBbE311142a19 | [StakingGOOGL.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |
| [rTSLA](https://www.bscscan.com/token/0xAbC2C0A1b16045311916DeC7a3336d09D82929a6) | 0xAbC2C0A1b16045311916DeC7a3336d09D82929a6 | [StakingTSLA.sol](https://github.com/risqprotocol/risq-options/tree/main/contracts/Staking)   |

### Chainlink price oracles

Hegic asset pricing for an option's underlying asset utilizes Chainlink oracles.

| Chainlink price oracles                                                          | Address                                    |
| -------------------------------------------------------------------------------- | ------------------------------------------ |
| [WBTC](https://bscscan.com/address/0x264990fbd0A4796A3E3d8E37C4d5F87a3aCa5Ebf)  | 0x264990fbd0A4796A3E3d8E37C4d5F87a3aCa5Ebf |
| [ETH](https://bscscan.com/address/0x9ef1B8c0E4F7dc8bF5719Ea496883DC6401d5b2e)   | 0x9ef1B8c0E4F7dc8bF5719Ea496883DC6401d5b2e |
| [BNB](https://bscscan.com/address/0x0567F2323251f0Aab15c8dFb1967E4e8A7D42aeE)   | 0x0567F2323251f0Aab15c8dFb1967E4e8A7D42aeE |
| [BCH](https://bscscan.com/address/0x43d80f616DAf0b0B42a928EeD32147dC59027D41)   | 0x43d80f616DAf0b0B42a928EeD32147dC59027D41 |
| [LTC](https://bscscan.com/address/0x74E72F37A8c415c8f1a98Ed42E78Ff997435791D)  | 0x74E72F37A8c415c8f1a98Ed42E78Ff997435791D |
| [PAXG](https://bscscan.com/address/0x7F8caD4690A38aC28BDA3D132eF83DB1C17557Df)   | 0x7F8caD4690A38aC28BDA3D132eF83DB1C17557Df |
| [COMP](https://bscscan.com/address/0x0Db8945f9aEf5651fa5bd52314C5aAe78DfDe540)  | 0x0Db8945f9aEf5651fa5bd52314C5aAe78DfDe540 |
| [CAKE](https://bscscan.com/address/0xB6064eD41d4f67e353768aA239cA86f4F73665a1)   | 0xB6064eD41d4f67e353768aA239cA86f4F73665a1 |
| [UNI](https://bscscan.com/address/0xb57f259E7C24e56a1dA00F66b55A5640d9f9E7e4)  | 0xb57f259E7C24e56a1dA00F66b55A5640d9f9E7e4 |
| [LINK](https://bscscan.com/address/0xca236E327F629f9Fc2c30A4E95775EbF0B89fac8)   | 0xca236E327F629f9Fc2c30A4E95775EbF0B89fac8 |
| [YFI](https://bscscan.com/address/0xD7eAa5Bf3013A96e3d515c055Dbd98DbdC8c620D)  | 0xD7eAa5Bf3013A96e3d515c055Dbd98DbdC8c620D |
| [AMZN](https://bscscan.com/address/0x51d08ca89d3e8c12535BA8AEd33cDf2557ab5b2a)   | 0x51d08ca89d3e8c12535BA8AEd33cDf2557ab5b2a |
| [GOOGL](https://bscscan.com/address/0xeDA73F8acb669274B15A977Cb0cdA57a84F18c2a)  | 0xeDA73F8acb669274B15A977Cb0cdA57a84F18c2a |
| [TSLA](https://bscscan.com/address/0xEEA2ae9c074E87596A85ABE698B2Afebc9B57893)   | 0xEEA2ae9c074E87596A85ABE698B2Afebc9B57893 |

### Where to buy $RISQ

$RISQ can be purchased through the Options Desk on the bonding curve.

| Purchasing venue contract                                                               | Address                                    | Github                                                                                                            |
| ---------------------------------------------------------------------------------------- | ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| [Bonding curve](https://www.bscscan.com/address/0xB6E72de684240d5815A5765aDf9D0ab835E0922C) | 0xB6E72de684240d5815A5765aDf9D0ab835E0922C | [BondingCurve.sol](https://github.com/risqprotocol/risq-options/blob/main/contracts/BondingCurve/BondingCurve.sol)   |

