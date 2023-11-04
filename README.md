# Installing ESlint and JSON package inside repository

### CLI commands:
<ol>
  <li>Initialize npm: "npm init"</li>
  <li>Install ESlint and JSON package: "npm install -D eslint"</li>
  
  <span>
  ```js
  npm install -D eslint
  ```
  </span>
  
  <li>Initialize ESlint: "npm init @eslint/config"</li>
  <li>Make Git ignore file: "touch .gitignore"</li>
  <li>Inside .giitignore file write: "node_modules/" (this step is for not pushing the node_modules folder to Github repo).></li>
</ol>
