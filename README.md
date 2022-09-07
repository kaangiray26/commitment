# commitment
Configure commit messages individually

## Installation
```
curl https://raw.githubusercontent.com/kaangiray26/commitment/main/commitment -o ~/.local/bin/commitment && chmod +x ~/.local/bin/commitment
```

## Quick start

* You can add `.commitment` to your .gitignore, otherwise just run the command `commitment`.
* Following lines will be ignored:
  ```
  - Empty lines
  - Lines starting with a #
  - Lines without commit messages
  ```
