# t-abraham

Web materials from UIdaho Special Collections, removed from university servers, recovered from archive.org 2018-08-24.

Available at: <https://www.lib.uidaho.edu/special-collections/t-abraham/>

Archive URLs:

- https://web.archive.org/web/20140117015933/http://www.uiweb.uidaho.edu/special-collections/ta.papers.htm
- https://web.archive.org/web/20140117015933/http://www.uidaho.edu/special-collections/papers/outreach.htm

Original URLs:

- http://www.uiweb.uidaho.edu/special-collections/Other.Repositories.html
- http://webpages.uidaho.edu/special-collections/

## Added to library main web

Contents of this repo were processed and added to the main web repository. 
Notes below detail the prep (but are not in this repo):

Content added to `/special-collections/t-abraham/`
and images to `/media/spec/t-abraham/`. 

In the main web Jekyll project, each page needs YML and permalink var. 
Added via:

`for f in *.htm; do sed -i "1i---\ntitle: $f\n# layout: none\nsection: special collections\npermalink: /special-collections/t-abraham/$f\n---" "$f"; done`

Links to images `src="pics/` and `href="pics/` now point to `/media/spec/t-abraham/`.
