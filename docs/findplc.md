# finding permissively-licensed content

## Bandcamp

!!! attention
    Google is used here because Bandcamp lacks its own license-based search. This is flawed solution to the problem, as it relies on Google's secondhand data, and returns all Creative Commons license varieties without the ability to narrow down the results. **It is likely to produce incorrect results, and it could stop working at any time.**

Enter `site:*.bandcamp.com/album/* intext:"some rights reserved" intext:"name your price" -intext:"individual track pages"` into the Google search bar, then sort the results by date.

## Free Music Archive

Use `http://freemusicarchive.org/search/?adv=1&music-filter-CC-attribution-only=on&music-filter-CC-attribution-sharealike=1&music-filter-public-domain=1&sort=track_date_published&d=1&page=1&per_page=200`.

### explanation

!!! note
    This is an incomplete explanation.

- The `music-filter-CC-attribution-only=on`, `music-filter-CC-attribution-sharealike=1`, `music-filter-public-domain=1` parts of the [query string](https://en.wikipedia.org/wiki/Query_string) search for music licensed *Attribution Only*, *Attribution-Sharealike*, or *Public Domain*.
- The `sort=track_date_publishe` part of the [query string](https://en.wikipedia.org/wiki/Query_string) sorts the results by date in descending order.
- The `per_page=200` part of the [query string](https://en.wikipedia.org/wiki/Query_string) displays 200 results per page.

## licensing
**No rights reserved: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).**