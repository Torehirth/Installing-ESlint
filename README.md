# Installing ESlint and JSON package through the Command Line

- Steps 1-3: These steps need to be done on every repository/project to make ESlint work.
- Steps 4-5: The node_modules folder is huge, and because of that, we don't want to push this folder to the remote (GitHub) repository.

---

### CLI commands:
<ol>
  <li>Creating JSON package:</li>

   ```HTML
  npm init
  ```

  <li>Install ESlint:</li>
  
  ```HTML
  npm install -D eslint
  ```
  
  <li>Create ESlint config file:</li>

  ```HTML
  npm init @eslint/config
  ```

  <li>Make Git ignore file (Git Bash):</li>

  ```HTML
  touch .gitignore
  ```

  <li>Inside .gitignore file write:</li>

  ```HTML
  node_modules/
  ```

</ol>

---
### GIT commands for pushing changes to repo:
<ol>
  <li>Stash files:</li>

  ```HTML
  git add .
  ```

  <li>Commit:</li>

  ```HTML
  git commit -m "commit message"
  ```

  <li>Push:</li>
  
  ```HTML
  git push
  ```

</ol>
