Citation Style for Science Podcasts
===

Journal- &amp; DOI-based citation style for inserting hyper-linked bibliography entries into WordPress-based podcast show notes.

How to Use
===

1. [Download & unpack this repository](https://github.com/KonScience/Citation-Style/archive/master.zip) 
2. Optional: Open .csl file with text editor to change `<title>` & `<title-short>` tags 
3. Import .csl into your reference manager. In [Zotero](https://www.zotero.org/download/), this works via `Preferences | Cite | Style | + `. Others have not been tested so far. Feedback welcome!
4. Paste/Insert bibliography entries into the "Text"-part of WordPress' editor. The "Visual" doesn't convert the HTML tags to hyperlinks.


Known Issues
===

- Zotero reports "... is not a valid CSL 1.0.1 style file..." upon import. Probably due to the extensive reduction of code.
- Currently, only journal articles with both DOI and URL are supported. Please make sure your reference manager imports both. 
