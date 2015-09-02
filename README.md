# smtr—A command line editor for StarMade templates

Smtr is a *tr*-like program, just for StarMade templates.

## Basic usage

To read an `infile.smtpl` and translate it to an `outfile.smtpl`, replacing the block IDs 286 and 444 by 75 and 296, respectively, run:

```shell
smtr -i infile.smtpl -o outfile.smtpl '286,444' '75,296'
```

Single block IDs (i.e. 286) as well as ranges (i.e. 286-287) are supported. See the `--help` page for further assistance.

## Prerequisites
- A Ruby runtime
- `gem install trollop`

## Disclaimer
[StarMade](//star-made.org) is a game by, and trademark of, Schine GmbH.
