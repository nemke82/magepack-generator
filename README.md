# magepack-generator
Tool to generate magesuite/magepack configuration file

Run docker image with: <BR>
```
docker run -t -i --rm magepack-generator bash
```
<BR>
Then generate magepack.config.js using following command (example): <BR>
```
magepack generate --cms-url="https://magentocommand.ml" --category-url="https://magentocommand.ml/category-2/category-2-1/category-2-1-1.html" --product-url="https://magentocommand.ml/category-2/category-2-1/category-2-1-1/simple-product-122.html"
```
<BR>
Once done copy magepack.config.js file to server and continue as per https://github.com/magesuite/magepack instructions from https://github.com/magesuite/magepack#bundling part.

<BR>
This tool is used just to generate magepack.config.js file instead compiling robust Chromium/Puppeteer within production Docker images.
