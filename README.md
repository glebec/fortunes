# 🥠 SFW Programming Fortunes

Database of programming wisdom fortune cookies for the classic [fortune](https://en.wikipedia.org/wiki/Fortune_(Unix)) program. Emphasis is on SFW (Safe for Work) content, unlike… well, many other fortune dbs.

The initial number of quotes is small, but will be expanded as the spirit wills.

## Contents

filename | data
---|---
`src/sfw-programming` | quotations
`src/sfw-programming.dat` | an index

## Installation

Simply copy the two source files into your `fortune` program's database folder. That will vary by installation but you might find it in `man fortune`.

## Usage

```sh
fortune sfw-programming
```

## Contributing

Remember to view the [contributing guide](CONTRIBUTING.md). Contributors with Node installed are encouraged to `npm i` / `yarn`, which registers a git-hook that automatically re-generates the index file before committing.
