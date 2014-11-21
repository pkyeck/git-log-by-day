git-log-by-day
==============

bash script to log git commits grouped by day (optionally filtered by author and set start/end date)


##Example output

```bash
$ git-log-by-day --author="Philipp Kyeck"

Logs filtered by author: Philipp Kyeck

[2014-10-16]
 * add gitignore
 * add first version of middleware
 * add error handling of render method
 * fix error handling of render method
 * use renderString method instead of just render
 * switch back to render() but with filename
 * add custom stuff: - template loader - loader logic - filters (static right now) - tags (static right now)

[2014-10-17]
 * cleanup code

[2014-10-28]
 * add max filter
 * bump to v0.2.0

[2014-10-31]
 * add html content-type to response
 * bump version to 0.2.1

[2014-11-13]
 * allow custom filters to be passed to middleware
 * bump version to 0.3.0
```
