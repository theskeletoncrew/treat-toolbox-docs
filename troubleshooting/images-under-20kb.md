# Images under 20KB

When running Pre-flight checks, you may receive a warning when your project contains image files that are less than 20KB in size. This is historically the minimum file size required when publishing your NFTs to decentralized storage through the Candy Machine cli.

In order to handle this, we've created a script that you can run on your images after export to inflate them, by adding harmless text to the image metadata.

The script can be found here:\
[https://gist.github.com/skeletoncrewrip/801ec261061a8bcfefe29459793ecfad](https://gist.github.com/skeletoncrewrip/801ec261061a8bcfefe29459793ecfad)

Run the script alongside the directory containing all of your images and metadata. The script expects the name of this directory to be `assets` and that all images will be inside of it, not in subdirectories.

To run the script, be sure to have `node` and a package manager like `npm` installed.&#x20;

Then install the png-metadata dependency:\
`npm i png-metadata`&#x20;

Finally, run the script (assuming you saved the gist above as `png_increase.mjs`):\
`node png_increase.mjs`

That's it! If it worked, all of your image files should now be 24KB.
