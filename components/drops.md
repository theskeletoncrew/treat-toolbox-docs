# Drops

A Drop describes a collection of NFTs that will be available to mint.&#x20;

Collections have several important properties:

* **Collection Name**: How you refer to this drop. It may have the same name as your project, or it might describe a single generation if you plan to drop multiple collections within the same [Project](projects.md).
* **Creators**: The [User Group](user-groups.md) that will be encoded into the metadata to receive royalties from any secondary sales.&#x20;
* **NFT Name**: The name that will appear in an owners wallet when viewing their NFT. This field allows [Metadata Templating](../advanced-features/metadata-templating.md).
* **Collection Type**&#x20;
  * **Generative**: these collections are created by merging many [Artwork](artwork.md) layers with transparent backgrounds chosen randomly through the [Traits](traits.md) you define for them.&#x20;
  * **Pre-rendered**: if your NFT artwork isn't random, but instead created in advance through a separate process, use this collection type.
* **Supply**: The total number of NFTs that should be created in this Drop.
* **Seller Fee Basis Points:** This is the fee you will take (and split with other creators) on any secondary market sales.&#x20;

{% hint style="warning" %}
**Important:** Basis points are defined as 1/100 of 1%.&#x20;

_Example: To take a 5% fee of all secondary sales, enter **500** for Seller Fee Basis Points._
{% endhint %}

* **Symbol**: Typically symbol isn't exposed to users, but it does live on the blockchain. Choose something representative of your collection. _(Skeleton Crew chose SKULL as its symbol for example)_
* **External **_****_** NFT URL**: provide a URL that each of your NFTs will offer a link to when viewed in the owners wallet. This field allows [Metadata Templating](../advanced-features/metadata-templating.md).
