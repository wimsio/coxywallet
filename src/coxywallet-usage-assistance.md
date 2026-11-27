# Coxy Wallet — Get Assistance

<img  alt="image" src="https://github.com/user-attachments/assets/a5291799-6c15-4f13-8c34-13d825f28bf6" />


**User guide | v2.4.4.61.8.4.3.9.18**

A practical guide to using the self-hosted multichain wallet. The Cardano deployment described here uses Preprod. Help is available from the header or mobile menu without signing in.

## Table of contents

1. About
2. Authentication
3. Blockchains
4. Send & Receive
5. ADA & Tokens
6. Collateral
7. DEX
8. Explorer
9. Prices
10. Coxy Dapp
11. Wallet Pro
12. Transactions
13. Settings

## 1. ℹ️ About

Get started with Coxy Wallet, a self-hosted multichain wallet.

<img alt="image" src="https://github.com/user-attachments/assets/3699bc41-b3ee-48b1-b9d4-865de6f505db" />


| Step | Action | How to use |
|---:|---|---|
| 01 | Open Wallet Home | Select Home. Help, Explorer, DEX and Prices are public; private wallet operations require authentication. |
| 02 | Choose a theme | Use Coxy, Ocean or Cardano to change the appearance. On a phone, open the hamburger menu for navigation. |
| 03 | Access your wallet | Use Authentication to unlock, create a new wallet, import an existing wallet or recover account access. |
| 04 | Understand the counters | Total Unique Wallets counts distinct active verified Cardano Preprod addresses. Total Cardano Txs counts distinct submitted or confirmed Cardano Preprod transaction hashes recorded in this installation. They refresh approximately every five minutes. |
| 05 | Test safely | The current Cardano wallet is configured for Preprod. Use test ADA (tADA); test assets are not real-money assets. |

**Good to know:** Never share your PIN, recovery words or private keys. Use only your trusted wallet website.

## 2. 🔐 Authentication

<img alt="image" src="https://github.com/user-attachments/assets/67dbf3a2-a7c7-4018-9c91-2fef3e479260" />

Choose the correct option in the Authentication panel.

| Step | Action | How to use |
|---:|---|---|
| 01 | Unlock | Enter your enrolled email and current seven-character PIN. Select Go or Unlock. The eye icon briefly shows or hides the PIN. |
| 02 | New | Enter your email, generate a seven-character code, confirm it, and select Create account & start wallet setup. Open the verification email and complete wallet creation. |
| 03 | Back up | After setup, securely save your original recovery words using the wallet-owned backup/export flow. Keep them offline. |
| 04 | Import | On a new browser, first verify account access and enroll the current PIN using Forgot PIN if required. Return to Import, enter the original account email, current PIN and original 24 words on your trusted device. |
| 05 | Restore | Read and acknowledge the trusted-device warning. Check account verification, then select Verify original address and restore wallet when available. Confirm the restored address matches the original. |
| 06 | Forgot PIN | Enter your registered email, select Go and follow the recovery email. A reset changes account access; it does not regenerate the original wallet keys. |
| 07 | Lock or sign out | Lock Wallet closes local wallet access. Sign out ends the account session. Choose the option appropriate to your needs. |

**Good to know:** Recovery words stay on the trusted browser. Do not paste them into support messages or dApps. Email recovery alone cannot restore lost blockchain keys.

## 3. 🌐 Blockchains

Select a blockchain and verify its network before using an address.

| Step | Action | How to use |
|---:|---|---|
| 01 | Unlock | Open Authentication > Unlock and access the wallet. |
| 02 | Choose a chain | In Blockchains Available, choose Cardano, Midnight, Bitcoin, Ethereum, Dogecoin, Solana, XRP, BNB Chain, Ethereum Classic or TRON. |
| 03 | Check network | Review the selected network, address and available balance. Cardano uses Preprod in this installation; other adapters have their own test networks. |
| 04 | Use supported actions | Only send or manage assets when the chosen adapter reports readiness. If an adapter is disabled or unavailable, do not attempt to send. |
| 05 | Customize list | Open Settings > Blockchains to choose which networks appear in this browser. |

**Good to know:** Selecting a blockchain does not activate an account or enable Mainnet. Do not send assets across incompatible chains or networks.

## 4. ↔️ Send & Receive

Use the existing wallet transfer and receive screens.

| Step | Action | How to use |
|---:|---|---|
| 01 | Receive | Unlock, select Receive from the wallet menu, choose the blockchain and copy the receive address or show its QR code. |
| 02 | Verify before sharing | Confirm the address and network. Ask the sender to use the same blockchain and test network. |
| 03 | Send | Open Send or Wallet. Choose the blockchain, enter the recipient address, select coins or a supported token, and enter the quantity. |
| 04 | Review | Select Go. Inspect the recipient, amount, asset, network, fee and available funds in the wallet review. |
| 05 | Approve | Approve only if all details are correct, using the wallet-owned PIN confirmation when requested. |
| 06 | Confirm | Use the transaction status or Explorer to check the original transaction hash. Refresh your balance after confirmation. |

**Good to know:** If submission is pending or uncertain, check the original transaction status before trying again. Do not send twice.

## 5. 🪙 ADA & Tokens

View, send and create Cardano test assets.

| Step | Action | How to use |
|---:|---|---|
| 01 | View ADA | Unlock Cardano Preprod. The Wallet balance shows available tADA. Keep enough tADA to cover fees and minimum-output requirements. |
| 02 | View tokens | Open Tokens > My Tokens. Search by name or policy ID, or select Refresh list. |
| 03 | Send a token | Select the token balance or token list action, choose the correct asset, enter a whole-number quantity and recipient, then review and approve. |
| 04 | Mint a token | Open Tokens > Mint Tokens (Cardano). If Secure Classic Mint is enabled, enter the asset name and quantity. An image is optional where supported. |
| 05 | Review and confirm | Prepare the mint, check policy, quantity, recipient and fee, approve locally, then check transaction status. Refresh My Tokens after confirmation. |
| 06 | MORF | Where the MORF issuer tools are enabled, authorized issuers may prepare and review mint/burn operations. Users can spend MORF in supported dApps according to their checkout rules. |

**Good to know:** A prepared draft is not a minted token. Verify the policy ID, and do not retry an uncertain mint or burn before checking its status.

## 6. 🛡️ Collateral

Prepare ADA-only outputs for Cardano smart-contract operations when required.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open Collateral | Unlock Cardano Preprod and select Collateral from the wallet menu. |
| 02 | Inspect UTxOs | Select Check my UTxOs. Review the ADA-only candidate outputs and eligibility. |
| 03 | Prepare an output | If necessary, use the collateral-sized self-transfer controls. The current screen permits 5–10 tADA for this purpose. |
| 04 | Review the transfer | Verify that the destination is your own address and approve through the normal wallet transaction review. |
| 05 | Refresh | Wait for confirmation, return to Collateral and refresh. Select or use an eligible output if the relevant transaction requires it. |

**Good to know:** Collateral may be consumed on script failure. Not every transfer or classic native mint needs collateral. Keep sufficient separate funding.

## 7. 🔄 DEX

Explore supported decentralized-exchange functions.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open DEX | Choose DEX in the header or wallet menu. On phones, use the mobile menu. |
| 02 | Check availability | Review the selected network and whether the exchange integration is active. A preview or quote is not a completed swap. |
| 03 | Choose assets | If swaps are enabled, choose the input and output assets and enter the quantity. |
| 04 | Review quote | Check the expected output, minimum received, price impact, fees and expiry where shown. |
| 05 | Authorize and verify | If a supported swap requests authorization, review the transaction in Coxy Wallet and check its final status in Explorer. |

**Good to know:** Swap availability depends on this installation. Follow the enabled DEX controls; do not approve an unfamiliar transaction.

## 8. 🧭 Explorer

Look up public Cardano Preprod blockchain information without unlocking.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open Explorer | Select Explorer. The dashboard shows block height, epoch, epoch transactions and active supply. |
| 02 | Search | Choose Auto detect or a supported search type. Enter a public transaction hash, block, address, pool, asset, stake credential, DRep or epoch. |
| 03 | Find details | Select Search, then open the matching result to inspect its public blockchain information. |
| 04 | Browse | Use Dashboard, Blocks, Pools, Assets or Epochs. Select View all where available. |
| 05 | Check a transfer | Search the original transaction hash. Check network, inclusion and confirmations before treating the transfer as complete. |

**Good to know:** Explorer is read-only. It never needs your PIN or recovery words. The network transaction total is different from Coxy Wallet usage counters.

## 9. 📊 Prices

View available market data and indicative prices.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open Prices | Select Prices in the header or mobile menu. |
| 02 | Choose an asset | Use the displayed asset list or search/filter controls if provided. |
| 03 | Read the quote | Check the asset, currency, price, time and any available market statistics. |
| 04 | Compare carefully | Use available refresh controls to retrieve updated data. Prices can move and the data source may be unavailable. |
| 05 | Return to Wallet | Use Home to return to authentication or your wallet. A price quote does not execute a trade. |

**Good to know:** Market data is indicative. Testnet assets do not have the same real-money value as Mainnet assets.

## 10. 🧩 Coxy Dapp

Connect to a registered application and review its requests.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open application | Select To Coxy Dapp when it is available. Confirm that you recognize the application website. |
| 02 | Connect wallet | Use the application’s Connect Wallet action. Open Coxy Wallet and review the requesting application, origin and requested permissions. |
| 03 | Approve connection | Sign in or unlock if required. Approve only the requested permissions you understand. Return to the dApp. |
| 04 | Use a service | Choose the application service. For checkout, check the invoice, amount, recipient and network in the wallet. |
| 05 | Confirm payment | Approve the reviewed transaction locally and wait for confirmation. Return to the requesting application and check its receipt/status. |
| 06 | Disconnect | Use the application’s Disconnect option. Check Connected Apps or the wallet’s available permission controls if revocation is uncertain. |

**Good to know:** Connection alone does not authorize spending. A disconnected dApp must reconnect before using wallet grants. Keep PIN and recovery words within the trusted wallet.

## 11. ⚡ Wallet Pro

Access advanced wallet functions supported by your installation.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open Wallet Pro | Unlock and choose Wallet Pro from the wallet menu. |
| 02 | Accounts | Review available wallet accounts and addresses. Choose the intended account before preparing any transaction. |
| 03 | Staking | Open Staking, refresh available pools, select a pool, prepare delegation review and verify the displayed transaction before signing. Check confirmation. |
| 04 | DRep | Open DRep, refresh the directory, choose a representative or supported registration/delegation action, review the exact Conway transaction, then check confirmation. |
| 05 | Digital Identity, Programmable Tokens, Privacy | Inspect readiness and available controls. These modules may be read-only, experimental or disabled; do not treat previews as live features. |
| 06 | Export Mnemonic | Use the secure Wallet Pro export screen only on your trusted device. Follow its verification requirements and store the backup offline. |

**Good to know:** Wallet Pro does not bypass the native wallet signing controls. Staking or governance transactions may require deposits or fees.

## 12. 🧾 Transactions

Review the history of recorded transactions for the selected wallet.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open Transactions | Unlock and select Transactions in the wallet menu. |
| 02 | Check context | Confirm the selected chain, network and wallet address before interpreting the history. |
| 03 | Inspect a record | Use available filters or the history list. Check the transaction hash, amount, direction and status where provided. |
| 04 | Verify on-chain | Open the explorer link or copy the original hash into Explorer. A pending or uncertain record is not final. |
| 05 | Refresh | Refresh the history or check the original status before attempting any repeat transaction. |

**Good to know:** History availability depends on the adapter and stored records. The public header transaction counter is an installation-wide database usage indicator, not a complete on-chain history.

## 13. ⚙️ Settings

Adjust the local wallet interface and access trusted account settings.

| Step | Action | How to use |
|---:|---|---|
| 01 | Open Settings | Unlock and select Settings from the wallet menu. |
| 02 | Blockchains | Choose which network buttons appear in this browser. Hiding a network does not delete its wallet or funds. |
| 03 | Network | Review adapter testnet configuration. Mainnet cannot be enabled by appearance settings. |
| 04 | Security | Use Change Sign-in PIN to access the verified recovery flow. Keep the original wallet backup available before resetting access. |
| 05 | Appearance | Show or hide theme buttons. Choose Coxy, Ocean or Cardano where the selector is available. |

**Good to know:** Do not clear browser storage as a troubleshooting step unless you have independently verified a usable backup and restoration procedure.

## Need more assistance?

Contact your Coxy Wallet administrator with the error code and a description of the issue. Never share credentials or recovery words.

---

Source: Help centre content embedded in the v2.4.4.61.8.4.3.9.18 release. Optional modules and adapter readiness depend on the installation; this guide does not independently verify live feature availability.
