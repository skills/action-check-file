# Action: Check file

Check file for expected changes.

Example use:

```yml
    steps:
      # Check that there is at least one header in the markdown file.
      - name: Check markdown syntax, header
        run: ./.github/script/check-file.sh
        env:
          file: "index.md"
          search: "# [a-zA-Z0-9]"
```

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
