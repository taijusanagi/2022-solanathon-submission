## RAKUGAKI

### Description

Rakugaki is the Japanese word for graffiti and is the perfect name for this exciting new product. Rakugaki is a revolutionary new way to create and share art. With Rakugaki, you can express yourself in ways you never thought possible.

With Rakugaki, you can create stunning images and mint them as non-fungible tokens (NFTs) on the Solana blockchain. Powered by stable diffusion and the Thirdweb Solana SDK, Rakugaki is the perfect tool for anyone looking to create and certify AI-generated images. Simply input the text, and Rakugaki will generate an image from it. You can then mint your NFTs on the Solana blockchain without needing a third-party service. So what are you waiting for? Try Rakugaki today and see how easy and fun it is to create beautiful things with AI!

### Pitch Deck

https://docs.google.com/presentation/d/1QO2Jr8rUt1Y3PjiPjknW34odrZYExiE58YlqvXjcwGg/edit?usp=sharing

### Deployed Service

https://2022-solanathon-submission.vercel.app/

### Demo Video

https://youtu.be/hK-KpZmwsFA

### How it works

![how-it-works](./docs/how-it-works.png)

1. Access Solana with Thirdweb SDK
2. Input prompt
3. [Backend] Generate Image by Stable Diffusion and sign by admin key
4. Preview image
5. This signature is to request the admin to mint the NFT
6. [Backend] Verify admin and user signature and mint NFT on Solana blockchain
7. NFT is minted and reflected in Thirdweb Dashboard

### Benefit

- Easy Onboarding for Solana's new user!
  - MetaTx for gas-less minting
  - AI-generated image for not thinking too much

### Thirdweb Dashboard

https://thirdweb.com/sol-devnet/A4bDc7ZLrWUXHKjF2hVg2Zp9zmfeay3k2UF2u7Wdm6Ch/

### Points to be improved

- Using signature mint when it is ready in Thirdweb Solana SDK
- The in-app market for exploring and selling/buying the Rakugaki NFTs

### Challenges

It is my first time developing on Solana! So I needed to learn from the beginning and set up a development environment.
