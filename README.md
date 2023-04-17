# Interface Token (archived info from Wayback Machine Nov 12th 2020)
This info is provided by the Wayback Machine, and is not guaranteed to be accurate.

(start of info)
# Not every smart contract or dApp needs its own token. 
Interface Tokens provide a transparent mechanism for a decentralized, transferrable, cross-platform blockchain identity. They are universal interface tokens that can be utilized by any project across the Ethereum ecosystem.
Developers can assign roles, permissions, and privileges to an Interface Token held within an Ethereum address versus assigning those same privileges directly to an Ethereum address.

The tokens are non-fungible and ERC721 compliant so each one is inherently guaranteed to be unique. 

Additionally a hash string in the format of an Ethereum block hash is permanently assigned to each token when minted. These hashes, which are also guaranteed to be unique to each token, provide opportunities for developers to create projects that react generatively to token holder interactions. 

Interface Tokens are pure and simple utility tokens that unlock a world of creative possibilities within the blockchain space. 

--
# How they work.
Interface Tokens are minted on demand and each token is assigned the following data:

Owner Address
TokenID
Unique Hash
Assigned Nickname (optional)
The unique hash stored on each token differs depending on the type of Interface Token that is minted. When minting a Bespoke Interface Token the stored block hash corresponds to the block hash of the Ethereum blockchain that matches the TokenID. With a Standard Interface Token the hash is automatically generated at the time of minting. You can choose which type of token you want to mint and developers can also choose which type of token, or both, to consider within their applications. All token hashes are formatted the same way and compatible regardless of whether they are minted as Bespoke Tokens or Standard Tokens.

The hash stored on the token is guaranteed to be unique to that particular token. This creates an opportunity for developers to apply generative characteristics to tokens (and their holders) when incorporating this additional data feature into applications.

--

# Access and Permissions
Most blockchain platforms currently consider a user's Ethereum address as their "identity" within that platform. Roles and permissions are granted to the Ethereum address because a user can prove ownership of the address through interfaces like Metamask.

Implementing Interface Tokens, a developer can assign a role or ownership within a platform to a token held by an Ethereum address instead of directly to an Ethereum address. This allows token holders to transfer roles to others by simply transferring the tokens themselves.

When a role or ownership is tied to an Ethereum address users cannot freely transfer their ownership or access within a platform without the developer manually transferring ownership of an account from one address to another. Without the developer's assistance a user may not be able to safely transfer ownership because the recipient would have to trust that the original owner will destroy the private key upon relinquishing the address.

Furthermore if there is value associated with a user's access or permissions within a platform and he or she chooses to sell that access, the developer would need to act as escrow to manage the exchange of funds and access for the two parties involved. If instead roles are tied to Interface Tokens those tokens can simply be listed on any exchange that recognizes the ERC721 standard and transactions can be settles in a decentralized fashion.

Interface Tokens are not spent when using them. They are simply tied to a user's Ethereum address and therefore can be used unlimited times on an unlimited number of different projects that choose to support the Interface Token.

# The Contract
Interface Tokens are non-fungible and generated through this ERC721 compliant smart contract. When a token is minted it is assigned a TokenID, a block hash, and an optional and editable nickname for human friendly identification.

Example:
TokenID: 1

Hash: 0x88e96d4537bea4d9c05d12549907b32561d3bf31f45aae734cdc119f13406cb6

Nickname: Numero Uno

Developers building on the Ethereum blockchain can create an identity tied to the TokenID or associated hash by simply querying the smart contract to confirm that a participant's Ethereum account controls a particular token.

Why the extra hash data?
A developer could simply use the TokenID itself to identify a user since the tokens are non-fungible and inherently unique. The hash stored on an Interface Token gives developers the ability to assign unique generative traits to each token. The hash can be used to trigger different experiences for each token holder with relative randomness.

# Some examples:

An artist could create a piece of generative digital art that reacts to a token holder's hash, giving that token holder an opportunity to interact with an art project in a way that is guaranteed unique and therefore "own" the result of the interaction.
Game developers can use a token holder's stored hash to generate the location of items or enemies in a dungeon or assign initial characteristics to a user's character. 
Lotteries and raffles can produce results based on a probability of a user's hash matching certain conditions.

-- 
# Cases 
# Multiple Wallets/Wallet Security

As cryptocurrencies become more mainstream, cryptocurrency wallets will become common items that everyone will have. People might have one super secure protected wallet that stores the title to their home and life savings, a slightly less secure spending wallet that needs to be accessed fairly regularly, and then one or more mobile wallet that only hold the bare minimum amount of valuables since they go with you wherever you go.

If a bank, for example, were to grant access to a safe deposit box based on proof of ownership of an Ethereum address, where your address is essentially your identity, you would want only a secure Ethereum address/wallet to be used for that purpose. That wallet/key pair used to access the safe deposit box, along with other critical funds or assets, might be sitting on a hardware wallet in a safe in your closet which you may be hesitant to leave the house with.

The bank could instead grant access to an Interface Token itself regardless of the Ethereum address it is connected to. In this scenario a user could simply and securely transfer that token to a mobile wallet which could be taken to the bank for access to the safe deposit box. Upon returning home he or she could just transfer the token back to the ultra secure wallet leaving that mobile wallet empty of critical assets. In this case the Interface Token is like your key to access your safe deposit box which you take with you only when you need it and store in a safe place all other times.

Using a mechanism like an Interface Token, we can simply transfer tokens to and from different addresses in order to transfer those roles and permissions instead of having to maintain multiple copies of various wallets each with their own purpose.

It is inevitable that once cryptocurrencies become mainstream a person might hold a dozen or more different addresses and managing all of that will be complicated enough as it is. Assigning roles to a more easily transferrable mechanism like a token versus to an actual address should make managing those roles and identities more practical. 

# CryptoCities.net

The popular blockchain game CryptoCities.net ties both in-game progress as well as player assets to a user's Ethereum address without use of a tokenized model. While the location assets within the game can be transferred by selling them through a marketplace, it is impossible for a user to transfer ownership of the progress made in the game itself to another user.

One might want to transfer ownership if, for example, there is value to the progress made in the game and another person would be willing to pay to take over the account. A user might also suspect that their Ethereum address is compromised and want to transfer their entire account to another Ethereum address without having to manually sell each owned location and then start over in terms of game progress. Any platform that assigns progress in a game, for example a saved game state, could assign that progress to a token rather than an Ethereum address giving the owner flexibility to transfer that token to a mobile Ethereum wallet for play on the go in the event they don't want to have the same Ethereum address on both their mobile device and their home computer.

Additionally the hash stored on a player's Interface Token could be used to generate special characteristics, both aesthetic and functional, for characters or elements incorporated into a game. Common, rare, and ultra-rare traits could be assigned to characters or locations based on the random hash stored on an Interface Token associated with a specific character or location based on generative algorithms put in place by the developer.

# Art Blocks

Art Blocks is a platform of smart contracts individually deployed by artists that are intended to be connected to works of generative art. The smart contracts, called Art Nodes, have a dynamic hash output that the artist can adjust to suit his or her needs. Users holding Interface Tokens can send ETH to the Art Nodes which will switch the output hash from the most recent block hash of the Ethereum blockchain to the hash stored on the user's Interface Token. A connected generative art project will use this hash as an input to control parameters and variables that dynamically shape the resulting art piece.

Since the token holder "owns" the hash, and that hash is guaranteed to be unique, a token holder is therefore the "owner" of the output of the connected project. Generative artists can create dynamic pieces where their patrons can pay to own their own unique edition of the artist's curated generative art. An artist or even industrial designer could interpret a user's Interface Token hash as the parameters to generate a sculpture or piece of furniture, for example, and produce and the file necessary for that user to have the object fabricated using a 3D printer or a CNC. Not only would the resulting piece be unique, but the owner of the piece also can prove ownership of the design by simply possessing the token that stored the hash that generated the design in the first place. 

# CryptoPunks 2.0

The CryptoPunks project pioneered the digital collectable industry with a series of 10,000 algorithmically pre-generated 8bit cartoon "punks" which were free to claim on the Ethereum Blockchain. The concept is brilliant and there is a robust secondary market for CryptoPunks still today, with special punks selling for upwards of $10,000 a piece.

Interface Tokens allow this type of crypto-collectable project to be reimagined. Instead of all of the punks having been pre-generated and then put up for people to claim, they would instead be generated on demand using the hash stored on a user's Interface Token. This means that instead of knowing what you're going to get in advance, the process would be more like opening a pack of trading cards with pre-specified odds of finding rare items inside. This method of distributing collectable assets removes the first mover advantage from the equation, giving all participants the same probability of generating a rare or unique digital asset.  

The next generation of crypto collectibles and crypto generated artwork can be created in real time using a token holder's hash, and that token holder can prove ownership of that asset by proving ownership of a hash which is easily accomplished through the transparency of the Ethereum blockchain.

# Contact
Our goal with the Interface Token project is to establish a pure and simple identity contract brand for blockchain applications. Our intention is to expand this brand onto all major token enabled blockchain platforms for a consistent product that can be trusted by end users and blockchain developers alike. We would love to hear from you!

Developers

Reach out to us to see how you can incorporate the Interface Token into your blockchain project. We are happy to set you up with plenty of Interface Tokens for testing or for distribution to your user base. 

Resellers

Interesting in purchasing Interface Tokens in bulk and reselling them or distributing them on your platform? Please don't hesitate to reach out. We are committed to a fair Interface Token distribution network of resellers and service providers.

Corporate

Interface Tokens make for a unique gift or incentive within the blockchain space as the ecosystem of projects utilizing the tokens expands. We are partnering up with service providers to create gift cards for the distribution of Interface Tokens.

# Standard Interface Token
Direct Contract Transaction - Instant

Standard Interface Tokens are minted automatically by sending ETH directly to the token contract. Upon receipt of funds the contract will mint your tokens and your Ethereum address will be credited automatically. The stored hash is generated for each token at the time of minting using variables present at the time of minting. Standard Interface Tokens are minted without an assigned nickname but can be assigned one by the token owner at any time.

# Bespoke Interface Token
Manual Minting Process - Delayed

Bespoke Interface Tokens have all of the same data elements as Standard Interface Tokens however the stored hash is specifically the block hash of the Ethereum blockchain corresponding to the block height of the TokenID. These "keepsake" tokens allow users to "own" previous block hashes of the Ethereum blockchain within this platform and are limited to the total number of Ethereum blocks in existence. Bespoke Interface Tokens can be assigned a nickname at the time of minting. Note that due to the manual minting process these tokens may take up to 24 hours to be credited to your Ethereum address.
https://etherscan.io/address/0x9c110de1fbc36dd87d256e0909dee6f03725937c 
--

# Art Blocks Engine (React Template)
[![GitPOAPs](https://public-api.gitpoap.io/v1/repo/ArtBlocks/artblocks-engine-react/badge)](https://www.gitpoap.io/gh/ArtBlocks/artblocks-engine-react)

This project is meant to be used as a template to build Art Blocks Engine web apps. It contains all of the pages and views necessary for users to browse projects, tokens and be able to purchase mints. This repository serves as a prototype or template. It assumes your core contract is `GenArt721CoreV3` and your minting contract is `MinterDAExpV2` with all sales priced in ETH. It is NOT intended for production use. Please modify for your needs and test extensively before using. Absolutely no warranty of any kind is provided. Please review from The MIT License:

## Warning

**THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.**

# Quick Start

Run `npm install` or `yarn` to install dependencies.

You will need to create a `.env` configuration file. You can get started by copying `sample.env` and renaming it as `.env`.

Run `npm start` or `yarn start` to run the project.

After making any changes to the `.env` file, you will need to restart the app.

## Customizing your configuration

In order to customize your specific implementation, you will need to edit the default configuration provided on the `sample.env` file. First of all, you will need to replace the contract addresses with your own.

You must specify an API key from [Infura](https://www.infura.io/) as well as a chain id in your environment file. Use `1` for mainnet or `5` for goerli. Alternative providers can be used by modifying the `src/components/Providers.tsx` file. Use multiple `.env` fiels to set up `development` or `staging` environments on `testnet` if you wish to do so.

There are additional configuration values you could customize like the number of projects per page, or tokens per page. You will find those parameters in `src/config.ts`.

# Sections and Features

This project includes wallet connection with [RainbowKit](https://www.rainbowkit.com/) and [wagmi.js](https://wagmi.sh/).

## Lander
- An empty landing page

## Projects
- Header/subheader
- Hero area with most recent project featured
- Title/artist name/description blurb
- Masonry grid of recent projects

## Project 
- Breadcrumb nav
- Status/date launched
- Cover image
- Link to token shown as cover
- Title/artist
- Number of invocations
- Mint button
- Description
- License/library
- Display notes (optional field)
- Code notes (optional field)
- Masonry token grid
- Sort (by date)
- Pagination

## Token
- Breadcrumb nav
- Date minted
- Token cover img with links to live/static views
- Owned by address or ens
- Title/artist name
- Features table
- Etherscan and OpenSea links

## Project list
- Masonry grid of projects
- Cover images
- Link to token shown as cover
- Title/artist name
- Description blurb
- Pagination
