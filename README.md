# Comics Ape NFT Minting dApp ( Udemy The Fullstack Nft Minting Website Course)

This a complete example of fullstack NFT minting dApp. **Comicsapesocialclub** is built with the purpose of providing an _entry point for future NFT Minting Website_ projects.

## Installation

You can use **the default Comicsapesocialclub smart contract** and play with it or you can also put **your own smart contract** and make changes as needed. _Remember to change `.env` file with your own variables._

Use the default **Comicsapesocialclub Smart Contract:**

```bash
  Download the zip file and unzip it

  cd comicsapesocialclub-nft-minting-dapp
  npm install            # Download packages
  npx hardhat compile    # Compile solidity contract into /artifacts
  npm run dev            # Run the dev server
```

## Tech Stack

**Client:** React, TailwindCSS, web3

**Server:** Alchemy, NextJS, Hardhat

## Support

For support, email codingwithdidem@gmail.com
rinkeby: {
      url: `${process.env.NEXT_PUBLIC_ALCHEMY_RPC_URL}`,
      accounts: [`0x${process.env.METAMASK_PRIVATE_KEY}`]
    }