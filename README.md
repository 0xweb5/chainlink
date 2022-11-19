# DAO Community Notes

A new way to distribute your rewards/grants to your community.

## Features:

1. Everybody can mint a note (a dynamic ERC3525 and ERC721 compatible NFT with tokens embedded) for your community.

2. Everybody can split the note to others or even your self as long as they have one.

3. Everybody can merge different notes together if they are the same slot (with same underlying assets, MATIC in this case).

4. Everybody can topup more funds (must same as the current underlying asset) to a note.

5. Everybody can withdraw funds from the note.

## Repos

[UI](https://github.com/crypto-notes/interface/tree/chainlink)

[Contract](https://github.com/crypto-notes/protocol)

[Subgraph](https://github.com/crypto-notes/notes-graph)

## Chainlink usage

Used the Chainlink price feed in the smart contract to get the current MATIC value.

[Get latest price in contract](https://github.com/crypto-notes/protocol/blob/chainlink/contracts/Cryptonotes.sol#L111)

[Display the formatted price in SVG](https://github.com/crypto-notes/protocol/blob/chainlink/contracts/NotesMetadataDescriptor.sol#L245)

[Get MATIC price in UI](https://github.com/crypto-notes/interface/blob/chainlink/src/components/Home/MyCryptonotes.tsx#L22)

## Upload NFT background image to IPFS/Filecoin

[Click to see the code](https://github.com/crypto-notes/interface/blob/chainlink/src/components/Home/MintDrawer.tsx#L82)
