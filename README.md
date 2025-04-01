# Wow, Another Static Site Generator (WASSG)
This project exists because of a gripe of mine with other SSGs: they abstract too much from the stuff it generates. This takes the opposite approach: it's designed to just substitute and stitch together chunks of text, and basically nothing else. This makes the programmer need to still rely on HTML and CSS, but also allows for making things simpler for websites with lots of pages via template systems or automatically generated index pages.

## Design Goals
1. Any file with .wassg added to the end gets processed
2. Useable as template system
3. Can compile data from other pages into automatically generated pages

