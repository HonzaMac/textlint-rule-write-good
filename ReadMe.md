# textlint-rule-write-good

[![Build Status](https://travis-ci.org/nodaguti/textlint-rule-write-good.svg?branch=master)](https://travis-ci.org/nodaguti/textlint-rule-write-good)
[![Dependency Status](https://david-dm.org/nodaguti/textlint-rule-write-good.svg)](https://david-dm.org/nodaguti/textlint-rule-write-good)
[![devDependency Status](https://david-dm.org/nodaguti/textlint-rule-write-good/dev-status.svg)](https://david-dm.org/nodaguti/textlint-rule-write-good#info=devDependencies)

[textlint](https://github.com/textlint/textlint) rule
to check your English styles with [btford/write-good](https://github.com/btford/write-good).

## Installation
```
$ npm install textlint-rule-write-good
```

## Usage
```
$ npm install textlint textlint-rule-write-good
$ textlint --rule textlint-rule-write-good some-text-to-proofread.txt
```

## Options
You can disable each types of checks via `.textlintrc`.

```
{
  "rules": {
    "write-good": {
      "passive": false,
      "thereIs": false
    }
  }
}
```

For available check types, see [btford/write-good#checks](https://github.com/btford/write-good#checks)