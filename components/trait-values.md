# Trait Values

The possible values that a [Trait](traits.md) can have are Trait Values. They have two properties:

* **Name**: the value name that will be shown in NFT metadata
* **Rarity**: the likelihood that an NFT will have this value in the overall [Trait Set](trait-sets.md) or [Drop](drops.md). Rarity is entered as a percentage between zero and one. Ex. 0.5 means 50% of your NFTs will have this value.

{% hint style="info" %}
The total Rarity of all of the Values in a [Trait](traits.md) do not necessarily need to add up to 1. In these instances the remaining percentage will be allocated to a _"None"_ value, which would not correspond to [Artwork](artwork.md).
{% endhint %}

Trait Values can each be entered individually, but you can also `Add a List of Values` (entered on separate lines) or `Import a List of Values` by providing them in a comma separated list (CSV file), each line with a value name and then a rarity.

For example, your `Colors.csv` might be defined as:

```
Red, 0.25
Blue, 0.5
Green, 0.1
Purple, 0.15
```

When adding a large number of Trait Values as a list, it may also be convenient in some cases to use the `Distribute Rarity Evenly` option to set a rarity across the entire group of traits at once. Of course, you may opt to give each value its own individual rarity – CSV import may be more convenient in that case.
