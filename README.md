Citation Style for Science Podcasts
===

Journal- &amp; DOI-based citation style for inserting hyper-linked bibliography entries into WordPress-based podcast show notes. It shall enhance both:
- the discoverability of the podcast episode by people who search the Internet for a study's author, title or DOI, and
- the ability of show note readers to quickly assess the relevance of the study to their interests

Example:
> John P. A. Ioannidis (2005) <a href="http://www.ncbi.nlm.nih.gov/pmc/articles/PMC1182327/" target="_blank">Why Most Published Research Findings Are False</a> (PLoS Medicine) DOI: <a href="http://dx.doi.org/10.1371/journal.pmed.0020124" target="_blank">10.1371/journal.pmed.0020124</a>

How to Use
===

1. [Download & unpack this repository](https://github.com/KonScience/Citation-Style/archive/master.zip) 
2. Optional: Open .csl file with text editor to change `<title>` & `<title-short>` tags 
3. Import .csl into your reference manager. In [Zotero](https://www.zotero.org/download/), this works via `Preferences | Cite | Style | + `. Others have not been tested so far. Feedback welcome!
4. Paste/Insert bibliography entries into the "Text"-part of WordPress' editor. The "Visual" doesn't convert the HTML tags to hyperlinks.


Known Issues
===

- Zotero warns about "... is not a valid CSL 1.0.1 style file..." upon import.
- Not all bibliography item types are supported yet. Look for arguments behind the occurances of `type="` [in the code](podcast-citation-style.csl) to find out which types are supported currently.
