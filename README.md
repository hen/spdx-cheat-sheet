# SPDX Cheat Sheet

## SPDX Specification

| URL      | Description |
| ----------- | ----------- |
| [License List](https://spdx.org/licenses/) | The list of License codes |
| [Exception List](https://spdx.org/licenses/exceptions-index.html) | The list of License Exception codes |
| [IDs](https://spdx.org/ids) | Short-form identifiers guidance |
| [Expressions](https://spdx.github.io/spdx-spec/appendix-IV-SPDX-license-expressions/) | SPDX Expressions spec guidance |
| [Tutorial](https://github.com/david-a-wheeler/spdx-tutorial) | Short SPDX Tutorial |

## Source Headers
    SPDX-License-Identifier: MIT

## Expressions

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

| Type        | Repo        | Language |
| ----------- | ----------- | ----------- |
| Document | [spdx/tools-golang](https://github.com/spdx/tools-golang) | GoLang |
| Expression | [kyoh86/go-spdx](https://github.com/kyoh86/go-spdx) | GoLang |
| Expression | [kemitchell/spdx.js](https://github.com/kemitchell/spdx.js) | JavaScript |
| Expression | [jslicense/spdx-expression-parse.js](https://github.com/jslicense/spdx-expression-parse.js) | JavaScript |
| Expression | [samcv/SPDX-Parser](https://github.com/samcv/SPDX-Parser) | Perl6 |
| Document | [spdx/tools-python](https://github.com/spdx/tools-python) | Python |
| Document | [ah450/spdx-tools-python](https://github.com/ah450/spdx-tools-python) | Python |
| Expression | [nexB/license-expression](https://github.com/nexB/license-expression) | Python |
| Expression | [heremaps/oss-review-toolkit](https://github.com/heremaps/oss-review-toolkit/tree/master/spdx-utils) | Kotlin (Java) |

## Other Tools

| Type        | Repo        | Language |
| ----------- | ----------- | ----------- |
| Autocorrector | [jslicense/spdx-correct.js](https://github.com/jslicense/spdx-correct.js) | JavaScript |
| Autocorrector | [librariesio/spdx](https://github.com/librariesio/spdx) | Ruby |
| Validator | [rust-lang-nursery/license-exprs](https://github.com/rust-lang-nursery/license-exprs) | Rust |
| Validator | [composer/spdx-licenses](https://github.com/composer/spdx-licenses) | PHP |
| Compatibility Validator | [librariesio/license-compatibility](https://github.com/librariesio/license-compatibility) | Ruby |
