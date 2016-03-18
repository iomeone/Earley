# 0.11.0.0

- Add `IsString Prod` instance
- Change the signature of `Terminal` to take a function `a -> Maybe b`, and add a new operator `terminal`
- Move `satisfy` to the `Derived` module
- Add the `token`, `namedToken`, and `list` operators
- Deprecate the `symbol`, `namedSymbol`, and `word` operators (use the above instead)
- Add the `listLike` operator

# 0.10.1.0

- Fix bug concerning nullable rules (#14)
- Add `runGrammar`

# 0.10.0.1

- Add changelog

# 0.10

- Remove `Args`, and use `Results` instead
- Make `parser` function not take input directly
- Remove redundant type parameter to `Grammar`.

# 0.9

- Optimise handling of nullable non-terminals
- Pass a record of arguments in the parse routine
- Add support for consecutive mixfix holes