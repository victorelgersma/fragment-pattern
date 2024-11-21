# fragment-pattern

A minimal version of the fragment pattern to dissect

The Fragment Pattern is a design approach where small, reusable chunks of content (fragments) are dynamically fetched and injected into a larger layout or UI. This pattern is commonly used in web development to reduce the amount of content initially loaded on a page, allowing specific sections of a webpage to be updated without requiring a full-page reload.

```zsh
npm run dev
```

go to /demo to see the fragment

https://excalidraw.com/#json=AAmAkhQsizCH6yGLIrNZG,XLBeq5iB2RLNv3JX50WlyQ

## To do

- [ ] compare with how HTMX does this
- [ ] compare with how astro server islands do this
- [ ] explore combining this with fetching data from horizon. How do we prevent many calls to horizon while also keeping the fetch to horizon on the server side


## Follow-up questions:

- What if the fragment contains client-side javascript?
- What if the fragment needs data from horizon?
