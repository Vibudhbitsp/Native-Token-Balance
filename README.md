# Native-Token-Balance
# Token Balance Checker

## Overview

This HTML file, along with embedded JavaScript, creates a simple web-based application for checking the token balance of an Ethereum wallet connected via MetaMask. The application supports multiple chains such as Mantle, Linea, and Kroma, each identified by a unique chain ID.

## Features

1. **Connect Wallet Button:** Allows users to connect their MetaMask wallet to the application.

2. **Token Balance Display:** Displays the token balance of the connected wallet in Ether (ETH) for the selected chain (Mantle, Linea, or Kroma).

3. **Percentage Change (Commented Out):** The code contains functionality to fetch and display the percentage change in the token balance over the last 12 hours. This section is commented out, but it can be uncommented for use.

4. **Alert System:** Alerts users if their token balance has decreased by more than 10% in the last 12 hours (also commented out).

## Prerequisites

- **MetaMask:** Users need to have the MetaMask extension installed in their browser.

## Usage

1. Open the HTML file in a web browser.

2. Click the "Connect Wallet" button to connect MetaMask to the application.

3. If the wallet is already connected, the token balance for the selected chain will be displayed.

4. Optionally, uncomment the percentage change section to enable and display the percentage change in the token balance.

## Supported Chains and Contracts

The application supports the following chains and corresponding smart contracts:

- **Mantle:**
  - Chain ID: 5000
  - Contract Address: 0xDCBc586cAb42a1D193CaCD165a81E5fbd9B428d7

- **Linea:**
  - Chain ID: 59144 (Custom ID)
  - Contract Address: 0xDCBc586cAb42a1D193CaCD165a81E5fbd9B428d7

- **Kroma:**
  - Chain ID: 255 (Custom ID)
  - Contract Address: 0x7afb9de72A9A321fA535Bb36b7bF0c987b42b859

## Troubleshooting

- If there are issues connecting the wallet or fetching the token balance, ensure that MetaMask is installed and unlocked, and the connected account has the necessary permissions.

- If using a custom network, make sure the chain ID and contract address in the `chainConfig` object are accurate.

## Disclaimer

This application is a basic example and should not be used in a production environment without further testing and security considerations.

Feel free to customize and extend the code to suit your specific needs.
