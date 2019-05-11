# SPDX Cheat Sheet

## SPDX Specification

| URL      | Description |
| ----------- | ----------- |
| [Expressions](https://spdx.github.io/spdx-spec/appendix-IV-SPDX-license-expressions/) | SPDX Expressions spec guidance |
| [License List](https://spdx.org/licenses/) | The list of License codes |
| [Exception List](https://spdx.org/licenses/exceptions-index.html) | The list of License Exception codes |

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

## Source Headers
    SPDX-License-Identifier: MIT
