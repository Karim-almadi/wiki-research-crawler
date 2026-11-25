# research-crawler

A small, non-commercial research crawler that reads public Wikidata, Wikipedia and Wikimedia Commons pages.

- Requests to each API are sent one at a time, with `maxlag` set; it backs off when asked and stops on repeated errors.
- Image downloads are thumbnails only, at most 3 at a time.
- User agent: `research-crawler/0.1 (https://github.com/Karim-almadi/wiki-research-crawler)`

If it causes any problem, please open an issue here and it will be stopped.
