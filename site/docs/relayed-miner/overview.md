---
sidebar_position: 1
---

# Overview

This guide outline how you can prevent or resolve a relayed miner on the Helium (HNT) network. The Helium network uses peer to peer networking to gossip between miners, save blocks, whilst maintaining a ledger of the blockchain. Your miner does this using your existing internet connection and relies on being able to send and receive data over TCP port `44158`.

This article outlines how you can configure your router to allow your miner to do this successfully and prevent the Helium app from marking your hotspot as 'Relayed'. When your hotspot is Relayed this p2p chatter can't occur which in turn stops you from participating in some proof of coverage rewards.
