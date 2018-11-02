# kotlin-docset

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
