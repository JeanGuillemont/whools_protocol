# whool protocol

### Reference
This is a fork of the [slugs-protocol](https://github.com/bernatfp/slugs-protocol) of bernatfp

### Summary
The whool protocol is an onchain url shortener with NFT art on top. It aims to make short url rewarding for their creator, funnier and safer for the visitors by integrating a splash screen before link redirection.

### Description
The whool protocol is an onchain and NFT powered url shortener allowing the creation and the management of whools. A whool is a string alias NFT mapping to an url selected by its owner. The protocol can be integrated in any frontend supporting the registration, management and/or resolution of whool requests for redirection. However, it's first use is through the [whool_application](https://whool.art/) reprensenting the main use case (at the time of writing) of the protocol. Feel free to innovate on it.

The protocol and its application aim to improve the accessibility of customized short urls and improve the visibility of artists by randomly promoting newly minted NFTs on platforms. In return, the protocol owner or the whool owner get referral fee on mints made from the link splash screen.

Any individual or project participating the growth of the protocol either by spreading the word or by creating an application where users create whools, will earn 30% referral fees on any custom whool minted.

### Genesis
The whool protocol is born from a multiple sided statement : 
- The awesome idea of bernatfp is an incredible opportunity to give to users part of the ownership of traffic they create instead of web2 actors
- The risk of hack and scams induced by short urls by hidding destination under a potentially and unmonitored false name, even more in web3 environment
- The difficulty for artists to make their work known outside their community, a growing factor due to the ongoing fragmentation of twitter community 
- The current low affordability of web3 customization tools which lower the positive effect on decentralization this customization would bring

### Whools ?

Whool is the mix of of "who" for the actor (user or entity) who create custom links and "wool" representing the links between those actors.

Whools are ERC721 NFT granting the owner to set the url corresponding to it. A whool can be :
- *Random*, in this case it will be a random string and will be free to mint (gas fee still needed). A random whool allow the owner to be referrer in 70% of case.
- *Custom*, in this case creator can choose the string used (if not already existing) and will require a static 0.001eth fee to be minted. A custom whool allow the owner to be referrer in 90% of case.

They are :
- *Affordable* : a custom whool can be minted at the fixed price of 0.001eth (a bit more than $2 at time of writing)
- *Perpetual* : custom or random whools are not rented by the user, once minted user owns his whool fully, forever
- *Transferrable* : the owner of a whool can gift it, transfer it and sell it 
- *1% royalty* : given whool affordability, permanent ownership, a 1% royalty fee on second sales seemed to be fair in case of speculation

### Developers
Dive into the /src directory for comprehensive contract documentation and source code.

Deployments
- Optimism Goerli: 0xCCD1f91f4cD7c52f091b68dCC66D9028eF0D4008
- Optimism Sepolia : 
- Optimism Mainnet: 0x7ed718678b22e65f803a5dc2b0107bb99c20a76d

### Disclaimer
- This contract is unaudited and could have bugs
- There is no URL validation at the contract level
- Safe URL redirection requires honest frontends to cooperate (outside whool application)

### License

MIT License
