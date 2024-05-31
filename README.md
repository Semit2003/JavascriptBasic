

This project demonstrates how to create, store, and list NFTs (Non-Fungible Tokens) using JavaScript. Each NFT is represented by an object containing metadata such as name, artist, year created, and description. The NFTs are stored in an array and can be listed and counted.

## Project Structure

- `nfts`: An array to hold the NFT objects.
- `mintNFT(name, artist, yearCreated, description)`: A function to create and store an NFT.
- `listNFTs()`: A function to list all NFTs by printing their metadata to the console.
- `getTotalSupply()`: A function to return the total number of NFTs minted.

## Functions

### mintNFT(name, artist, yearCreated, description)

This function takes four parameters to create an NFT object and stores it in the `nfts` array.

**Parameters:**
- `name`: The name of the NFT.
- `artist`: The artist who created the NFT.
- `yearCreated`: The year the NFT was created.
- `description`: A brief description of the NFT.

### listNFTs()

This function iterates through the `nfts` array and prints the metadata of each NFT to the console.

### getTotalSupply()

This function returns the total number of NFTs stored in the `nfts` array.

## Usage

To use this script, simply copy the code into a JavaScript file and run it using a JavaScript runtime such as Node.js.
