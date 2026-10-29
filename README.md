# Solana Validator Transaction Ordering Measurement Tool

Measurement project for Superteam Earn bounty: Inside the Block (How Solana Validators Order Transactions).

## Overview
This tool measures how Solana validators order transactions within a block, focusing on validators running different client software or forks.

## Features
- Docker Compose reproducible
- Dry-run by default; real sending only behind --live flag with 0.05 SOL spend cap
- Raw data export (tx sigs, slot numbers) for verification
- README explaining design and limitations

## Status
Work in progress. Measurement requires Solana mainnet access.
