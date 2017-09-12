- Setup CI and coveralls
- Improve test coverage
- Generate source map for easy debugging
- `mermaid.init` should throw exception, no need to call `mermaid.parse`
- mermaid inline style overrides html, body padding
    - trigger a syntax error to see how the padding changes
    - should rewrite mermaid inline style generation code
- There is a global lodash `_`