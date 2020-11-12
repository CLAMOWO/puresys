WebP Express 0.18.2. Conversion triggered using bulk conversion, 2020-11-01 13:01:35

*WebP Convert 2.3.2*  ignited.
- PHP version: 7.4.10
- Server software: Apache

Stack converter ignited
Destination folder does not exist. Creating folder: [doc-root]wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2020/11

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]wp-content/uploads/2020/11/Grid.png
- destination: [doc-root]wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2020/11/Grid.png.webp
- log-call-arguments: true
- converters: (array of 9 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- alpha-quality: 85
- encoding: "auto"
- metadata: "none"
- near-lossless: 60
- quality: 85
------------


*Trying: cwebp* 

**Error: ** **exec() is not enabled.** 
exec() is not enabled.
cwebp failed in 13 ms

*Trying: vips* 

**Error: ** **Required Vips extension is not available.** 
Required Vips extension is not available.
vips failed in 2 ms

*Trying: imagemagick* 

**Error: ** **exec() is not enabled.** 
exec() is not enabled.
imagemagick failed in 2 ms

*Trying: graphicsmagick* 

**Error: ** **exec() is not enabled.** 
exec() is not enabled.
graphicsmagick failed in 2 ms

*Trying: wpc* 

**Error: ** **Missing URL. You must install Webp Convert Cloud Service on a server, or the WebP Express plugin for Wordpress - and supply the url.** 
Missing URL. You must install Webp Convert Cloud Service on a server, or the WebP Express plugin for Wordpress - and supply the url.
wpc failed in 5 ms

*Trying: ewww* 

**Error: ** **Missing API key.** 
Missing API key.
ewww failed in 66 ms

*Trying: imagick* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]wp-content/uploads/2020/11/Grid.png
- destination: [doc-root]wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2020/11/Grid.png.webp
- alpha-quality: 85
- encoding: "auto"
- log-call-arguments: true
- metadata: "none"
- quality: 85

The following options have not been explicitly set, so using the following defaults:
- auto-filter: false
- default-quality: 85
- low-memory: false
- max-quality: 85
- method: 6
- skip: false

The following options were supplied but are ignored because they are not supported by this converter:
- near-lossless
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Quality: 85. 
Reduction: 61% (went from 5253 bytes to 2054 bytes)

Converting to lossless
Reduction: 53% (went from 5253 bytes to 2472 bytes)

Picking lossy
imagick succeeded :)

Converted image in 257 ms, reducing file size with 61% (went from 5253 bytes to 2054 bytes)
