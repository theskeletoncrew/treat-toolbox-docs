# Traits

Traits are the key component that provide randomness in the generative process. Each Trait corresponds to a list of possible [Trait Values](trait-values.md) that, based on their rarity, might be chosen to be part of a generated NFT.

Traits and their values normally include both assigned [Artwork](artwork.md) and appear in the NFT's metadata. There are some circumstances where you don't want a trait to include artwork or metadata (that's where metadata-only and artwork-only traits come in).

* **Name**: The Trait name that will be shown in the NFT's metadata.
* **Layer (z-index)**: The stacking order of the artwork for this trait. Lower numbered layers will appear below higher numbered layers in the final [Composite](composites.md).
* **Exclude from duplicate detection**: Check this box for any Trait that should not be considered when detecting duplicates (ex. background color as [recommended by SOL Big Brain](https://twitter.com/SOLBigBrain/status/1451979437805871107)).&#x20;
* **Metadata-only Traits**: use this for a Trait that should appear in Metadata, but is not associated with artwork. For example, a "role" or "favorite xyz".
* **Artwork-only Traits**: use this to add artwork to the generation process that shouldn't be called out specifically in the metadata. One example might be adding a textured layer above the top layer of your [Composite](composites.md).
* **Always Unique**: [Trait Values](trait-values.md) are typically reused across many NFTs in a collection. It is only the combination of all Trait Values that are ensured to be unique. However, if you have a particular Trait that should be unique on its own (ex. a "Name"), you c
