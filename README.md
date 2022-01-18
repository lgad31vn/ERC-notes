
 
# ERC-notes
- ERC = Ethereum Request for Comment ====> Token Standard
- ERCs are application-level standards in the ETH ecosystem ==> smart contracts standard for tokens 
- ERC is pretty much the form of memoradum describing methods, behaviors, research, or innovations applicable to the working of the Ethereum ecosystem.
- ETC is a set of the rules that Smart Contracts implement and leverage


# ERC20
- The most common and well-known ERC within crypto community
- ~ 99% issued ICO tokens on ETH network implements this standard
- A simple set of functions that a token should have
- https://github.com/lgad31vn/ERC-notes/blob/main/ERC-20.sol


# ERC223
### Advandtages:
- Created to solve ERC20 standard
- Avoid accidentally lost tokens inside contracts that are not designed to work with sent tokens
- ERC223 transactions consume less gas than ERC20

### Disadvandtages:
- ERC223 is a proposal, not a standard ==> none high-profile ICO tokens on top of this proposal
- Might need some modifications to support token deployed with ERC223


# ERC721
- This proposal's goal is to creat NFT
- ERC721 makes it easy to create marketplaces for NFTs
- ERC721 has ownership functions
  + ownerOf: returns the address of the owner of a token.
  + approve: grants or approves another entity the permission to transfer tokens on the owner’s behalf
  + takeOwnership: optional function that acts like a withdraw function since an outside party can call it to take tokens out of another user’s account


# ERC1155
- An NFT standard mainly used for NFTs, a newer generation of ERC721
- Unique token that supports NFTs AND fungible tokens AND semi-fungible tokens.  
- ERC1155 allows one contract create various types of NFTs.
- Previously, under ERC-20 or ERC-721, you had to deploy a separate contract for each fungible or non-fungible token.
- Gas fees are cut by 90%
- ERC1155 allows transfer multiple types of tokens (NFTs, FTs, Semi-FTs) at the same time. 






## source: 
 - https://medium.com/wepower/erc-standards-to-move-ethereum-forward-erc-20-erc-223-erc-721-e1712456449d
 - https://www.quicknode.com/guides/solidity/how-to-create-and-deploy-an-erc-721-nft
 - https://moralis.io/erc1155-exploring-the-erc-1155-token-standard/
