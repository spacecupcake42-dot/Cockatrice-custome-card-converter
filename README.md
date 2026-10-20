How to use it
Drop one or more card images onto the page (PNG, JPG or WebP), or add cards by hand. Each image becomes a card named after its filename, and underscores become spaces.
Fill in the name, mana cost, type line, rules text, P/T and rarity. Mana cost accepts {2}{U}{R} or 2UR.
Set the set code and name at the top (it defaults to CUS). The XML preview on the right updates as you type.
Click Download ZIP. It contains customsets/<SET>.xml and pics/<SET>/<Card Name>.png, with each image renamed to match its card.
Extract the ZIP into your Cockatrice data folder and restart Cockatrice.
Mana value, colors, color identity, main type and table row are filled in automatically from the mana cost and type line. You can also paste an image URL per card to set picURL instead of bundling the image.
No OCR: The tool doesn’t read text off the card images, so you type the card details yourself.
Offline ZIP: The ZIP button needs internet the first time, because it loads a small zip library from a CDN. “Download XML only” works offline.
