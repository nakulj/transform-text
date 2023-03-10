# Transform Text

Quickly transform text with regexes.

## Usage

```sh
transform-text PATTERN FIND REPLACE [DIR]
```

Eg. To change all commas inside square brackets into semicolons, you can run:

```sh
transform-text '\[.*?]' , :
```

## Requirements

- RipGrep
- sd
