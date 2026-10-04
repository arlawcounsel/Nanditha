# Nanditha Portal V5

A full-screen, non-scrolling interactive story. Navigation is scene-based: arrows, wheel, keyboard, or the on-screen controls. The first screen deliberately gives false confidence before the assignment reveal.

## Add your photos
Put your real images in:

- `assets/photos/nanditha-01.jpg`
- `assets/photos/ameer-nanditha-01.jpg`
- `assets/photos/nanditha-02.jpg`

You can replace those filenames, but if you do, update the matching `src` values in `index.html`.

## Add your contact number
Open `index.html` and find:

`const CONFIG={name:'Nanditha',phone:'+919999999999'};`

Replace the placeholder with your real number in international format, e.g. `+9198XXXXXXXX`.

The Call Ameer button will then open the device's phone dialer using `tel:`.

## Run
This is a static site. Open `index.html` directly, or serve the folder with any static server.

## Design
The visual direction uses a restrained Apple-like product-page language: system UI typography, large type, strong whitespace, black/white/blue palette, and full-screen scene transitions. It is not an Apple-branded or Apple-copied website and does not bundle Apple's proprietary font assets.
