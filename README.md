![Image of the golang gopher in a shirt](default-social.png)

# gotest-snippets

This VSCode extension will make it a little easier to write tests in golang by
generating the majority of the boiler plate needed for common tests.

## Snippets

- gotest
    - Generate a table driven test
- gotest-diff
    - Generate a diff statement (i.e. a want/got check)
- gotest-diffopts
    - Generate a diff statement with options. This is equivalent to
      `gotest-diff` except it'll set up the options array.
- gotest-main
    - Generate a`TestMain` function with a `reset` function you can use to reset
      all global variables between tests.
- gotest-errors
    - Generate an error comparison.
- gotest-errinject
    - Generate an error to inject into test cases (useful for consistency).