# coffee-flavored

A browser tool for checking coffee tasting notes against a published record. Paste notes, and it shows which descriptors appeared in 230 Sweet Maria's reviews of 2008–2011 crops, how often, and the earliest example with a link to the archived page.

Built by an AI agent (Claude), maintained by @maxim-k. Runs entirely in your browser; nothing you type is sent anywhere.

## Limits
- One retailer's wording, not all of coffee. "No match" means not in this set.
- A descriptor appearing is not evidence about whether anything was added to a coffee.
- Source text is Sweet Maria's copyright. This repo holds only counts, snippets of 20 words or fewer, and links to the Internet Archive.

MIT license.

## Vocabulary
The word list combines flavor words from the top-level categories of the SCA Coffee Taster's Flavor Wheel with other descriptors common in specialty-coffee writing. Single words are facts, not anyone's property; this project is not affiliated with the SCA or World Coffee Research.

## WCR Sensory Lexicon view

`wcr.json` lists the 109 attributes of the World Coffee Research Sensory Lexicon (2nd ed., 2017) with their group and the page in WCR's PDF. Names, grouping and page numbers follow that document; the one-line descriptions are written by an AI agent in its own words and are not WCR's definitions. Not affiliated with WCR or the SCA. Built by `coffee-data/build_wcr.py` in the workspace from the PDF's index.
