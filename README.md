# Tools

A collection of HTML web tools built for artists and developers. Every tool runs entirely in the browser; no server, no build, no dependencies.

## Tools

### Image
| Tool | Description |
|---|---|
| Matte Generator | Place non-square images onto a matted canvas with a custom background |
| Seamless Scroll Generator | Split a wide image into slices for Instagram carousel scrolls |
| socialcropper | Crop images to preset aspect ratios for Instagram, Bluesky, and Threads |
| watermarker | Overlay an image watermark onto photos with adjustable opacity and position |

### Color
| Tool | Description |
|---|---|
| colorformats | Convert between HEX, RGB, HSL, and CMYK |
| gradientgen | Create and export linear, radial, and corner CSS gradients |
| harmonygen | Generate complementary, triadic, analogous, and other color harmonies |
| paletteextract | Extract a dominant color palette from any uploaded image |
| palettegen | Build and export a color palette from hand-picked colors |
| colorpicker | Sample the color of any pixel in an uploaded image |

### Creative
| Tool | Description |
|---|---|
| artenhance | Add color noise or film grain overlays to artwork |
| favicongen | Resize and export favicon PNGs at common sizes |
| imageclip | Trim transparent edges from PNGs to the tightest bounding box |
| imageconvert | Convert and resize images between PNG, JPG, and WebP |
| pastedownload | Paste an image from clipboard and instantly download it |
| svgtopng | Convert SVGs to high quality PNGs at 1×, 2×, or 4× scale |

### Text
| Tool | Description |
|---|---|
| textdifference | Paste two text blocks and see a highlighted diff |
| wordcount | Count words, characters, sentences, paragraphs, and reading time |
| textscratch | Freeform scratchpad with case conversion, sorting, find and replace |

### Code & Data
| Tool | Description |
|---|---|
| barcodegen | Generate barcodes in Code 128, EAN, UPC, and more |
| qrgen | Generate QR codes from any URL or text string |
| encodedecode | Encode/decode Base64, URL, Hex, Binary, and generate MD5/SHA hashes |

## Usage

All tools are self-contained HTML files. Open any file directly in a browser, or serve them from any static host. The index page (`index.html`) links to all tools.

## Stack

Vanilla HTML, CSS, and JavaScript. A small number of CDN libraries are used where appropriate (JsBarcode, qrcodejs, JSZip, diff-match-patch).
