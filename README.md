## Installation

1. Clone this configuration:
  ```bash
  rm -rf ~/.atom && git clone git@github.com:thomas88/atom-config.git ~/.atom
  ```

2. Setup `apm`:
  ```bash
  apm stars
  ```  

3. Install starred packages:
  ```bash
  apm stars --install
  ```
  
4. Install linters:
  ```bash
  npm install -g eslint
  npm install -g jsonlint
  ```

## Adding new packages

```bash
apm star minimap
apm stars --install
```
