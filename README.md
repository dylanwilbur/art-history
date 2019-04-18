# Introduction

This is my collection of notes for AP Art History in the 2018-2019 school year. Due to days I was absent, or days my laptop died, the collection is not complete, but there is enough here where I can safely say I have notes on the majority of CollegeBoard's 250 required works.

## Using the notes
I use this site personally so I can access my notes wherever I am, but there are some useful use cases I have found to be helpful.

You can:
- Review by unit using the side bar
- Review a particular work using the search bar
- Review a particular topic using the search bar, and view all works containing a certain key phrase(try **religion**, **power**, **trade**)
- Search for something under a specific title(try `context:trade`)

### Note on searching:
Searching on the wiki uses a highly adaptable search engine([Lunr](https://lunrjs.com) if you're curious). This lets you do some really cool stuff in terms of searching:
- search for multiple terms separated by a space: `foo bar`:
  - will return results matching either `foo` OR `bar`
- search for parts of words with wildcards, represented with a `*`:
  - `foo*` will search for all words beginning with `foo`
  - `*oo` will search for all words ending with `oo`
- apply weight to certain words:
  - `+foo bar -baz` will search for documents that must contain `foo`, might contain `bar`, and don't contain `baz`

More info [here](https://lunrjs.com/guides/searching.html)
