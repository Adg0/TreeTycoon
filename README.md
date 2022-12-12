# :deciduous_tree: Silvanus: Grow seedling into a meta tree.

:warning: *This is a proof of concept, not to be used in production environment.*

## Summary

Silvanus is an `on-chain` dynamic NFT game.

Players water seedling NFTs to grow them into a tree.

Players race to grow their seedling before the tree NFT dies from `flood` or `wild fire` happens.

The goal of the game is to promote forestation and bring people together.

[![Silvanus](https://imgur.com/pmMPeI6.png)](https://youtu.be/DHCMM8Xy254 "Silvanus")

[Demo Video](https://youtu.be/DHCMM8Xy254 "Silvanus")

[Live Demo](https://rectangular-sedate-anger.glitch.me/)

The front end application is written with vite and generated from unity.
The repository for the Front-End is available here: https://github.com/adapole/silvanus-frontend

## Overview

Multiplayer mode is the major focus of our build, to bring people together we must provide a media of communication.

A voip voice communication channel is built into the game so anyone in the room can talk with each-other.

And a support for almost all modern hardware devices, from VR & AR devices to smart-phones and PC widens the reach of our game.

### Game play

To win the game all you need to do is raise your seedling into a tree.
Water the seedling with `H2O` token consistently until it becomes a tree.

Some events are triggered by game master, like `Rain` and `Wild fire`.

Rain supplies all silvanus NFT holders with water token(H2O) and on occasion it causes `Flood` for small seedlings.

`Wild Fire` is also started by game master to level the playing field so seedlings get a chance to grow and compete with bigger trees.

Floods destroy the seedlings but you get a water token airdrop nonetheless.

To survive wild fire event, pledge water for fire extinguishing; that is `approve` spending to contract to drain water incase a fire happens.

So `Pray` for protection from `Flood` and `Fire` at the temple.
Or use some `Magic Potion` NFT to revive your tree if it dies.

# Smart Contract

The `silvanus NFT` is responsible for processing all growth event. The program is responsible for implementing all the logic for the game. And so it is a dynamic NFT.

The `potion NFT` is used to revive dead trees, any account that holds silvanusTree NFT gets exponential potions power minted during mint call to `potion contract`. Potion NFTs are thus dynamic NFT as well.

The `H2O token` is used to grow the silvanusTree NFT.

## Contact

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/silvanus_tree.svg?style=social&label=Follow%20%40silvanus_tree)](https://twitter.com/silvanus_tree)
