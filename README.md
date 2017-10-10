git-log-by-day
==============

Bash script to log git commits grouped by day (optionally filtered by author and set start/end date)

## Install instructions

Copy the `git-log-by-day.sh` to the `/usr/local/bin` folder for all users to have access  
**or**  
create a `~/bin` folder and add that to your `PATH` so only your user can access it.

## Example output

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

![Screenshot of script's output](https://cloud.githubusercontent.com/assets/870980/5142927/36121412-718a-11e4-9ee9-2a2a127416cb.png)
