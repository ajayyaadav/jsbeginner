// Step 1: Create a variable to hold your NFTs
let nfts = [];

// Step 2: Function to mint an NFT and store its metadata
function mintNFT(name, description, owner) {
    const nft = {
        name: name,
        description: description,
        owner: owner,
        timestamp: new Date()
    };
    nfts.push(nft);
}

// Step 3: Function to list all NFTs' metadata
function listNFTs() {
    nfts.forEach((nft, index) => {
        console.log(`NFT ${index + 1}:`);
        console.log(`Name: ${nft.name}`);
        console.log(`Description: ${nft.description}`);
        console.log(`Owner: ${nft.owner}`);
        console.log(`Minted On: ${nft.timestamp}`);
        console.log('---------------------');
    });
}

// Step 4: Function to get the total supply of NFTs
function getTotalSupply() {
    return nfts.length;
}

// Step 5: Calling the functions
mintNFT("CryptoKitty", "A cute digital cat", "Alice");
mintNFT("PixelPunk", "A retro-style digital avatar", "Bob");

console.log("All NFTs:");
listNFTs();

console.log(`Total Supply: ${getTotalSupply()}`);
