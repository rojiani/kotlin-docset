# kotlin-docset

**NOTE**: I made these docsets because at the time, the only Kotlin docset available in Dash was outdated (Kotlin 1.1). 
An updated Kotlin docset is now available in the Dash app (in the *User Contributed* section), so I recommend using it.
Here's the GitHub repo: [Kotlin Dash docset](https://github.com/Kapeli/Dash-User-Contributions/tree/master/docsets/Kotlin).

---

Downloadable docsets for Kotlin 1.2, 1.3, etc. can be found in [Releases](https://github.com/rojiani/kotlin-docset/releases).

---

*kotlin-docset* is a docset for [Dash.app](http://kapeli.com/dash)
containing the documentation for [Kotlin](http://kotlinlang.org).

## Prerequisites

This docset only builds on *Mac OS X*, since it requires `tiffutil`.

Install via *Homebrew* (`brew install ...`):

- `wget`
- `imagemagick`

Install via *Bundler* (`bundle install`):

- `nokogiri`

## Building the Docset

The following command generates `Kotlin.docset` in the `_output` folder.

```
./run
```

## License

This project is licensed under the terms of the MIT license. See the LICENSE file.
