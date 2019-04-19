# Introduction

This is my (incomplete) personal collection of notes for AP Art History.

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

## Contributing
This project is version controlled with git, so for those inclined, the source is hosted on github [here](https://github.com/dylanwilbur/art-history). Since the notes are not conclusive in the slightest, I welcome any and all additions or changes. You can learn to do so through [this app](https://desktop.github.com/).

#### What needs work
- Images for the 250 works
- Cleaning up formatting
- Adding works which are missing
