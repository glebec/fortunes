Please follow these guidelines when making a PR:

## Content

* Keep quotes safe for work!
* Double-check that a quote is not already included.
	* There may be small discrepencies between quotes; please research the most accurate version.

## Formatting

* Fortunes should be separated by a line containing just `%`.
* Please enclose fortune quotations in straight quotes (`"`).
* Signatures go on the very next line preceded by a tab, two hyphens (`--`), and a space.

## File Generation

* After adding the quotes, run `strfile src/sfw-programming` to re-generate the `dat` index.
	* Or, if you have Node installed, `npm i` or `yarn` to register a git hook which does this automatically before every commit.
