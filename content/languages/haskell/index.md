---
title: Haskell
description: Haskell on Codewars
slug: /languages/haskell
tags: [haskell]
---


## Versions

- GHC 9.2.5 ([LTS Haskell 20.10](https://www.stackage.org/lts-20.10))

## Test Frameworks

- [Hspec](http://hspec.github.io/)
  - [Codewars Hspec Utility Functions](https://github.com/codewars/hspec-codewars)

## Timeout

12 seconds

## Packages

### GHC 9.2.5

```yaml
# From package.yaml
# See https://www.stackage.org/lts-20.10 for versions
dependencies:
- base >= 4.7 && < 5
- attoparsec
- haskell-src-exts
- hspec
- hspec-attoparsec
- hspec-codewars # https://github.com/codewars/hspec-codewars
- hspec-contrib
- hspec-formatters-codewars # https://github.com/codewars/hspec-formatters-codewars
- hspec-megaparsec
- HUnit-approx
- lens
- megaparsec
- mtl
- parsec
- persistent
- persistent-sqlite
- persistent-template
- random
- regex-pcre
- regex-posix
- regex-tdfa
- split
- text
- transformers
- vector
```

## Services

None

## Language ID

`haskell`
