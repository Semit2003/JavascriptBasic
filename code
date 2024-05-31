// Create a variable to hold your NFTs
let nfts = [];

// This function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata,
// and store it in the variable above.
function mintNFT(name, artist, yearCreated, description) {
    // Create an NFT object
    const nft = {
        name: name,
        artist: artist,
        yearCreated: yearCreated,
        description: description
    };
    
    // Store the NFT object in the nfts array
    nfts.push(nft);
}

// Create a "loop" that will go through an "array" of NFTs
// and print their metadata with console.log()
function listNFTs() {
    for (let i = 0; i < nfts.length; i++) 
        console.log(nfts[i]);
}
// Print the total number of NFTs we have minted to the console
function getTotalSupply() {
    return nfts.length;
}

// Call your functions below this line

// Mint some NFTs
mintNFT('Taj Mahal', 'Ustad Ahmad Lahauri', '1653', 'A white marble mausoleum located in Agra, India.');
mintNFT('Mysore Palace', 'Henry Irwin', '1912', 'A historical palace in the city of Mysore in Karnataka, India.');
mintNFT('Gateway of India', 'George Wittet', '1924', 'An arch-monument built in the early twentieth century in the city of Mumbai, India.');
mintNFT('Red Fort', 'Ustad Ahmad Lahauri', '1648', 'A historic fort in the city of Delhi in India.');
mintNFT('Qutub Minar', 'Qutb-ud-din Aibak', '1193', 'A minaret that forms part of the Qutb complex, a UNESCO World Heritage Site in the Mehrauli area of Delhi, India.');

// List all NFTs
listNFTs();

// Print the total number of NFTs minted
console.log("Total NFTs: " + getTotalSupply());
