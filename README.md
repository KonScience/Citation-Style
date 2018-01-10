Citation Style for Science Podcasts
===

Journal- &amp; DOI-based citation style for inserting hyper-linked bibliography entries into WordPress-based podcast show notes. It shall enhance both:
- the discoverability of the podcast episode by people who search the Internet for a study author(s), title or DOI, and
- the ability of show note readers to quickly assess the relevance of the study to their interests

Example:
> John P. A. Ioannidis (2005) <a href="http://www.ncbi.nlm.nih.gov/pmc/articles/PMC1182327/" target="_blank">Why Most Published Research Findings Are False</a> (PLoS Medicine) DOI: <a href="https://doi.org/10.1371/journal.pmed.0020124" target="_blank">10.1371/journal.pmed.0020124</a>

How to Use
===

1. [Download & unpack this repository](https://github.com/KonScience/Citation-Style/archive/master.zip) 
1. Optional: If you want this style to appear with a more memorable name then `Podcast` in Zotero, open the .csl file with a text editor and change `<title>` & `<title-short>`. 
1. Import the .csl into your reference manager. In [Zotero](https://www.zotero.org/download/), this works via `Preferences | Cite | Style | + `. Others have not been tested so far. Feedback welcome!
1. Assuming you already have imported your reference(s) into Zotero (see [here](https://www.zotero.org/support/getting_stuff_into_your_library) for instructions), right-click on the item(s), select `Create Bibliography from Item(s)... | Citation Style: Podcast`, `Output Mode: Bibliography` and `Output Mode: Copy to Clipboard` and click `OK`. Zotero should auto-save these settings, so you'll not have to click everything again next time.
1. Paste/Insert the bibliography entry into the `Text`-part of WordPress' editor. Switch back to `Visual` to continue writing the show notes ;-) You are writing show notes, aren't you?


Known Issues
===

- Zotero reports "... is not a valid CSL 1.0.1 style file..." upon import. Not sure why, copy-and-pasting of bibliography items still works.
- Not all media types are supported yet. To find out which, search for `type=` [in the code](podcast-citation-style.csl). [Here's a list](http://citationstyles.org/downloads/specification.html#appendix-iii-types) of all possible types. Pull requests welcome ;-)
