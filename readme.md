# Dave the Hedgehog Support for NFTs

Welcome to the official README for understanding and utilizing NFT metadata for "Dave the Hedgehog." NFTs (Non-Fungible Tokens) are unique digital assets on the blockchain, often representing ownership over digital or physical assets. Metadata is the backbone of NFTs, providing essential details that define and authenticate each token.

## What is NFT Metadata?

NFT metadata includes critical information about the NFT, such as its name, description, associated images, and other attributes. This metadata can be stored directly on the blockchain or on an external server using a decentralized storage solution like IPFS (InterPlanetary File System).

### Importance of Metadata

Metadata plays a vital role in:

- **Authenticity**: Validates the uniqueness and original ownership of the NFT.
- **Interoperability**: Ensures that NFTs can be used and recognized across various platforms and marketplaces.
- **Information**: Offers potential buyers detailed insights into the NFT's properties, such as its origin, creator, and unique features.

## Example of a JSON Metadata File

Below is a sample JSON file representing the metadata for "Dave the Hedgehog":

```json
{
  "name": "Dave the Hedgehog",
  "description": "Dave the Hedgehog is a digital collectible character with spikes of wisdom. As adventurous as he is wise, Dave loves exploring digital realms.",
  "image": "ipfs://bafybeib4e6jdpzat4y2ek3jn57uhethnzvdnxyaem25cupjohxd23shuie",
  "attributes": [
    {
      "trait_type": "Background",
      "value": "Sunset"
    },
    {
      "trait_type": "Spikes",
      "value": "Glowing"
    },
    {
      "trait_type": "Personality",
      "value": "Wise"
    },
    {
      "trait_type": "Accessory",
      "value": "Glasses"
    }
  ],
  "properties": {
    "files": [
      {
        "uri": "ipfs://bafkreigh2akiscijoplcfenmjbffzzyf5m6zylqslcmda57jxn33rifnu",
        "type": "image/png"
      }
    ],
    "category": "image",
    "creators": [
      {
        "address": "0x123456789abcdef",
        "share": 100
      }
    ]
  }
}
