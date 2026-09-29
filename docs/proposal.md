# ChainTris

_Battle-royale Tetris where entry fees form a SOL prize pool for the last block standing_

## Summary

ChainTris is a 99-player style Tetris battle royale where players pay a small SOL entry fee that gets pooled into a smart contract prize. Attack lines are sent between players in real time, and the final standings trigger an automatic on-chain payout to the top finishers. A commit-reveal scheme locks in each match's RNG seed so results are verifiable and cheat-resistant.

## Target users

Competitive casual gamers who enjoy Tetris 99-style multiplayer and want real stakes

## Problem

Existing Tetris battle royale games have no real stakes or verifiable fairness, so competitive players lose interest quickly.

## Solution

Combine real-time multiplayer Tetris with a Solana escrow contract that pools entry fees and pays winners automatically based on a verifiable match outcome.

## MVP features

- Real-time multiplayer Tetris with attack-line mechanics for up to 8 players (MVP scale)
- SOL entry fee escrow via Anchor program with automatic prize distribution
- Commit-reveal RNG seed to guarantee fair, verifiable piece sequences
- Wallet-based login and match history dashboard
- Simple spectator mode for ongoing matches

## Chains

Solana

## Tech

Anchor, Rust, Colyseus, React, Phaser.js, Solana Wallet Adapter, WebSockets

## Category

Gaming

## Why now

Solana's low fees and fast finality make microtransaction-based gaming economics viable in real time, and on-chain gaming has strong hackathon and grant support right now.

## Roadmap

- Scale matchmaking to 50-99 concurrent players
- Add spectator betting on ongoing matches
- Introduce seasonal ranked ladders with NFT trophies
