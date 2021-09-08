# HTML Three.js WebXR Template

This template is very similar to the ThreeJS WebXR template, with the minimal modifications to add [three-tiltloader](https://github.com/icosa-gallery/three-tiltloader). 

At a minimum, the template provided should only need your model, named `model.glb`, adding to this folder to work correctly.

All HTML content needs to be minted in a zip file. You can have multiple files inside your zip, however there are a few requirements you can't miss.

1. The HTML file can only be called index.html
2. The file should have a thumbnail image to be displayed until the user clicks to interact on your NFT. The image can be png, jpg or a gif. you just need to update the <metadata> reference inside the HTML file.
3. At the moment calls to external sites are being blocked, even if they seem to work locally when you are testing. So any dependency needs to be included locally in the zip.

When zipping this template, ensure to set your compression software to use full paths to files, instead of relative paths, otherwise the content will not display correctly! You can confirm this in the preview window before minting.

Regardless of what content you want to display (three.js, pixi.js, canvas, p5.js, shaders etc), it should always be full width and full height (window.innerWidth and window.innerHeight) so please dont forget to include your own resize function.

Hope you guys enjoy!
Hicetnunc team
