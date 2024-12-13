# Solana Raydium Bundler Using JITO and LOOKUPTABLE

## Contact
telegram: @Takhi77

You can contact me here if you have any problems with this repo then we can decide comfortable contact way.

## Overview

Jito is supporting the bundle service that you can confirm 4 transactions (This is maximum from my experience) at once.

It provides methods for creating, buying from 21 wallets, and selling tokens when you want.

This is the step of My bundler.

##1. Creating TOKEN with metadata

##2. Creatig Market

##3. Creating wallets to buy tokens from the pool you creating.

##4. Creating Lookuptable

##5. Extending Lookuptable and simulations of each transactions to bundle

##6. Bundle createPool transaction and 3 transactions buying from 21 wallets.

##7. Revoke mint authority, freeze authority and LP burn

##8. Sell tokens at once from 21 wallets using bundle when you want

##9. Gathering Sol from 21 wallets you bundle buy and sell

# Updated Raydium Bundler

MVP version of previous bundler is creating the pool and bundle buy with same amount of sol.
But it has drawbacks, cuz the balance of tokens from 21 wallets vary a lot because of bonding curve logic of Raydium.
So, in updated version, I implemented presimulation of bundler wallets, so being estimating the amount of solana to buy from each wallet.
And also amount of tokens in each wallet.
And In updated version it is seperating the dev wallet and funding wallet for bundlers.
By doing that, bundler wallets will not be detected as dev wallets.
There are several updates in updated version of Raydium Bundler.
