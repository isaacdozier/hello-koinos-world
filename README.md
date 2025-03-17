# Hello Koinos World

A super simple webpage that connects to the Koinos blockchain and displays basic information.

## What is this?

This is a minimal "Hello World" application for the Koinos blockchain. It consists of a single HTML file that:

1. Makes a basic REST API call to the Koinos blockchain
2. Displays information about the current state of the blockchain

## How to use

### View online

Just visit the GitHub Pages link for this repository:
https://isaacdozier.github.io/hello-koinos-world/

### Run locally

1. Download the `index.html` file
2. Open it in any web browser
3. Click the "Get Blockchain Info" button

That's it! The page will connect to the Koinos blockchain and show you information about the latest block.

## What you'll see

When you click the button, you'll see:
- The current block height
- The timestamp of the latest block
- The ID of the latest block
- The chain ID
- Which RPC endpoint was used

## How it works

The page tries to connect to several public Koinos RPC endpoints until it finds one that works. Then it makes two simple API calls:
- `chain.get_head_info` - Gets information about the latest block
- `chain.get_chain_id` - Gets the blockchain's chain ID

## Deployment

This project is designed to be deployed on GitHub Pages:

1. Fork or clone this repository
2. Enable GitHub Pages in your repository settings
3. Select the main branch as the source

Your site will be available at `https://your-username.github.io/repository-name/`.
