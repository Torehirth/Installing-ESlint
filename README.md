# Installing ESlint and JSON package through the Command Line

- These steps need to be done on every repository.
- The node_modules folder is huge, and because of that, we don't want to push this folder to the remote (GitHub) repository - (step 4-5).

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

  <li>Inside .giitignore file write: "node_modules/"</li>

  ```html
  node_modules/
  ```

</ol>
