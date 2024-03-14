# Action: Check file

_This is not a course._ See https://skills.github.com for our list of available courses.

Check file for expected changes.

Example use:

```yml
    steps:
      # Check that there is at least one header in the markdown file.
      - name: Check markdown syntax, header
        uses: skills/action-check-file@v1
        with:
          file: "index.md"
          search: "# [a-zA-Z0-9]"
```

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
