# Prototypes

The Prototyp3 repositories present examples and use cases using Cartesi Rollups technology. Each repository highlights aspects of Cartesi Rollups technology: how the technology works, some specific characteristics, functionalities, how to perform some tasks with the technology, how to integrate with other Blockchain technologies.

**Prototyp3 repositories are not final products and should be considered as informative examples only. Everyone using these repositories as the basis for their own projects must do their own audits and due diligence to create a product.**

To download this repository and all the examples execute the commands below:

```shell
git clone https://github.com/prototyp3-dev/prototypes.git
git submodule update --init --recursive
```

## Coin Toss

## Echo Plus

```
Cartesi Rollups version: 0.8.x
```

[Echo-plus](https://github.com/prototyp3-dev/echo-plus) DApp exercises different aspects of technology in a extended echo DApp example form. It echoes assets back to the sender emiting vouchers, it accepts special commands to make the DApp emit framework messages, it also accept json messages that allows to process sql commands, sort numpy arrays, process images and emit a voucher to mint an ERC721 with the correspoonding CID.

## Echo Voucher

```
Cartesi Rollups version: 0.9.x
```

The [echo-voucher](https://github.com/prototyp3-dev/echo-voucher) DApp is an echo dapp for assets. It emits emitting vouchers back to the owner of any assets deposited. There is also a [sunodo echo voucher version](https://github.com/prototyp3-dev/echo-voucher-sunodo).

## Frontend Web

```
Cartesi Rollups version: 0.9.x
```

The [Frontend Web](https://github.com/prototyp3-dev/frontend-web-cartesi) project is a react based web interface with that allows the interaction with any Cartesi Rollups DApp. It has Metamask integration, it sends messages to the DApp by Inspects and generic Inputs, it allows to use the Dapp Address Relay and Portals, and also lists Notices, Reports, Vouchers (and allows execution of Vouchers). The project can be used to kickstart a web interface for a Cartesi ROllups DApp.

## Ornithologist

```
Cartesi Rollups version: 0.8.x
```

Thr [Ornithologist](https://github.com/prototyp3-dev/ornithologist) DApp exercises an integration with IoT W3bstream servers to gather device location data, sumarize it, and input to a Cartesi Rollups DApp. The Cartesi Rollups DApp compares the sumarized data with a endangered bird public database to generate a Layer 2 non-fungible asset which represents birds. The bird asset can be used to play a top-trumps-like game and later can be minted on Layer 1.

## Token Prices

## Web2 to Cartesi

## Odds and Evens Game DApp

```
Cartesi Rollups version: 0.8.x
```

The [Odds and Evens](https://github.com/prototyp3-dev/odds-and-evens) shows how to use the Commit-Reveal logic to implement an Odds and evens game. In Commit-Reveal schemes, each player submits a "commitment" for a secret message. After all players sent their commitments, they send the "reveal", the data that allows the recovery or proof of the initial commitment. Players cannot deny or fake the actions they have commited. The odd and evens game dapp use the Commit-Reveal logic to implement simultaneous actions, but the scheme can be used to simulated hidden actions, generate an unbiased shared state (such as seed for random numbers), and many other use cases.

## Go Rollups

```
Cartesi Rollups version: 0.9.x
```

[Go Rollups](https://github.com/prototyp3-dev/go-rollups) provides a high level framework for golang Cartesi Rollups DApp. It has serveral utilities that helps and simplifies  the DApp development.

## Csv Processor

```
Cartesi Rollups version: 0.9.x
```

[Csv Processor](https://github.com/prototyp3-dev/csv-processor) Dapp presents an application layer protocol that allows statements to assert facts about data, avoiding sending data to the DApp.
