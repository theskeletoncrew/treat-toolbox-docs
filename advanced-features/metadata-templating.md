# Metadata Templating

Fields that support Metadata Templating allow you to substitute dynamic values into your metadata by using the format: `{{METADATA_TITLE}}` or `{{NUMBER}}`.

For example, to have your fifteenth NFT have a name like "Monke #15", your NFT Name should be defined as: `Monke #{{NUMBER}}`

Similarly, if you want to use the value of one of your NFT's traits in your NFT's url, you can use its trait title to cause the substitution. For example, if everyone of your NFTs has an Address trait with a value like "25 Main St", you can make that the name of your NFT be defining NFT Name as `{{ADDRESS}}.`
