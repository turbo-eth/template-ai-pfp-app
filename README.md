![marketplace](https://github.com/turbo-eth/template-ai-pfp-app/assets/3408362/e748e22f-889f-4bb5-a26a-9912121216de)
# Ethereal Nexus

The Ethereal Nexus is Web3 application for combining artificial intelligence and blockchains.

The template is currently under construction and open to the TurboETH community bounty contributors.

### Initial Feature Requests
- [ ] Players in the "Web3 Metaverse" can create a unique 1-of-1 PFP NFT generated using an image generation model trained in their personal images.

## 🧱 Project
Create a Web3 application that combines Dreambooth AI and ERC721 NFTs. 

The application should allow users to generate personalized "Web3 Metaverse" profile pictures. 

The PFPs will be generated using Dreambooth, which is AI program that can be trained on object, like a person, and recreate that object in a variety of different environments. The NFT will be minted on the Optimism network, which is a popular Ethereum rollup and permantely stored on either IPFS or Arweave.

### Application Features

1. Purchase NFT Access Control Pass
User are required to purchase an access control NFT for 10 USDC. The cost of the NFT will be used to run the servers required to generate the AI profile pictures. 

The access control NFT is separate from the PFP NFT. And is used as solely as purchase receipt and as an API access control trigger.

2. Upload Images to Server
User should be able to upload 5-10 photos of themselves on a private server. The images should be stored in Vercel object storage and be erased after the PFP has been generated.

3. Generate AI Profile Pictures
User should be able to generate 100 unique profile pictures using a model trained on the upload images in the previous step. Users can save all of the hi-res images at no additional cost.

4. Select Favorite & Mint on Blockchain
Users should be able to select a single PFP, which will be uploaded to IPFS or Arweave, and minted on the Optimism L2 rollup.

**Required Functionality:**
1. Dreambooth API Integration
2. ERC721 Access Control Smart Contract
3. ERC721 PFP Smart Contract
4. IPFS Image Upload

**Developer Tasks:**
- [ ] Create turbo monorepo using [TurboRepo](https://turbo.build/)
- [ ] Clone [TurboETH](https://www.turboeth.xyz/)  Web3 Application template `main` branch.
- [ ] Clone [TurboETH](https://github.com/turbo-eth/template-hardhat-sol) smart contract boilerplate.
- [ ] Create ERC721 Access Control NFT using Solbase (smart contracts)
- [ ] Create ERC721 AI PFP NFT using Solbase (smart contracts)
- [ ] Create Image Upload Service (application)
- [ ] Create API that communicates with external Dreambooth API (application)

#### Example Application Template
The Places TurboETH template is good example of how to setup a turbo monorepo that includes independent TurboETH application and smart contract packages.

The [WAGMI CLI](https://wagmi.sh/cli/getting-started) is used to connect the application and smart contracts. React read, write and events are automatically generated.

## Mockups
The [initial mockups and ideas](https://www.figma.com/file/vhv5ucJdlYL7AKrfZFJrxb/Portrait?type=design&node-id=1%3A360&t=s5l9yovThewchi93-1) are available on Figma and are free to download, copy and update.

![combo](https://github.com/turbo-eth/template-ai-pfp-app/assets/3408362/a68b7bc8-8922-47e6-a7f4-d91fe3d9da9c)



