# gg
Command line google search - like googler - except it actually works.  ;-)

So, I got tired of getting the dreaded "No results." from googler, so I tried to fix it - gave up after a few minutes and figured it'd be easier to just re-write the thing myself.

# Usage:

gg your-search-text

# Results:

Title:  result #3 title<br />
Snippet:  result #3 summary text<br />
Link:  result #3 url<br />

Title:  result #2 title<br />
Snippet:  result #2 summary text<br />
Link:  result #2 url<br />

Title:  result #1 title<br />
Snippet:  result #1 summary text<br />
Link:  result #1 url<br />

Notice:  Results are in reverse order.  Because errrm... because I say so.

Requires:  NodeJS 17.5 or higher (because it uses fetch - I like fetch).
