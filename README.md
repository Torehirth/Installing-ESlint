# Installing ESlint and JSON package through the Command Line

These steps needs to be done on every repository.

### CLI commands:
<ol>
  <li>Initialize npm: "npm init"</li>

   ```html
  npm init
  ```

  <li>Install ESlint and JSON package: "npm install -D eslint"</li>
  
  ```html
  npm install -D eslint
  ```
  
  <li>Initialize ESlint: "npm init @eslint/config"</li>

  ```html
  npm init @eslint/config
  ```

  <li>Make Git ignore file (Git Bash): "touch .gitignore"</li>

  ```html
  touch .gitignore
  ```

  <li>Inside .giitignore file write: "node_modules/" (this step is for not pushing the node_modules folder to Github repo).></li>

  ```html
  node_modules/
  ```

</ol>
