# Installing ESlint and JSON package through the Command Line

- Steps 1-3: These steps need to be done on every repository/project to make ESlint work.
- Steps 4-5: The node_modules folder is huge, and because of that, we don't want to push this folder to the remote (GitHub) repository.

---

### CLI commands:
<ol>
  <li>Initialize npm: "npm init"</li>

   ```HTML
  npm init
  ```

  <li>Install ESlint and JSON package: "npm install -D eslint"</li>
  
  ```HTML
  npm install -D eslint
  ```
  
  <li>Initialize ESlint: "npm init @eslint/config"</li>

  ```HTML
  npm init @eslint/config
  ```

  <li>Make Git ignore file (Git Bash): "touch .gitignore"</li>

  ```HTML
  touch .gitignore
  ```

  <li>Inside .giitignore file write: "node_modules/"</li>

  ```HTML
  node_modules/
  ```

</ol>
