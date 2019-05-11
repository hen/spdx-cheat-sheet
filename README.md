# SPDX Cheat Sheet

## SPDX Specification

| URL      | Description |
| ----------- | ----------- |
| [Expressions](https://spdx.github.io/spdx-spec/appendix-IV-SPDX-license-expressions/) | SPDX Expressions spec guidance |
| [License List](https://spdx.org/licenses/) | The list of License codes |
| [Exception List](https://spdx.org/licenses/exceptions-index.html) | The list of License Exception codes |

## Source Headers
    SPDX-License-Identifier: MIT

## Quick Notes on Expressions

### OR expressions
    (LGPL-2.1 OR MIT OR BSD-3-Clause)
### AND expressions
    (LGPL-2.1 AND MIT AND BSD-2-Clause)
### WITH expressions
    (GPL-2.0+ WITH Bison-exception-2.2)
### Or Later expressions
    (LGPL-2.1+)
### Order  
    +
    WITH
    AND
    OR



## Parsers

| Repo      | Language |
| ----------- | ----------- |
| [spdx/tools-golang](https://github.com/spdx/tools-golang) | GoLang |
| [kyoh86/go-spdx](https://github.com/kyoh86/go-spdx) | GoLang |
| [kemitchell/spdx.js](https://github.com/kemitchell/spdx.js) | JavaScript |
| [jslicense/spdx-expression-parse.js](https://github.com/jslicense/spdx-expression-parse.js) | JavaScript |
| [samcv/SPDX-Parser](https://github.com/samcv/SPDX-Parser) | Perl6 |
| [spdx/tools-python](https://github.com/spdx/tools-python) | Python |
| [ah450/spdx-tools-python](https://github.com/ah450/spdx-tools-python) | Python |
