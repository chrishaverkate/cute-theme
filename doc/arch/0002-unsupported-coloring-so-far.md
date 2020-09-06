# 2. Unsupported coloring so far

Date: 2020-09-05

## Status

Proposed

## Context

Some tokens are not parsed by VSCode, which makes certain tokens undifferentiable.

## Decision

Add grammars to the extension to support additional tokens.

These tokens are not differentiable by default, so they cannot be colored as desired:
* Single line Doxygen for members: `///< comment about var`

## Consequences

What becomes easier or more difficult to do and any risks introduced by the change that will need to be mitigated.

## References / Links

[TextMate Language Grammars](https://macromates.com/manual/en/language_grammars)
[VSCode Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
[VSCode Grammars Contribution Point](https://code.visualstudio.com/api/references/contribution-points#contributes.grammars)
