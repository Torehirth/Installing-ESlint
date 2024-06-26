# Installing ESlint and creating JSON package through the Command Line

- Steps 1-3: These steps need to be done on every repository/project to make ESlint work.
- Steps 4-5: The node_modules folder is huge, and because of that, we don't want to push this folder to the remote (GitHub) repository.
- The ESlint extension in VS Code has to be installed as well, but this is a one-time install.


### CLI commands:

<ol>
  <li>Creating JSON package:</li>

   ```HTML
  npm init
  ```

  <li>Install ESlint:</li>
  (installs version 8)
  
  ```HTML
  npm install -D eslint@8  
  ```
  
  <li>Create ESlint config file:</li>

  ```HTML
  npm init @eslint/config
  ```

  <li>Make Git ignore file:</li>
  
*Git Bash:*

  ```HTML
  touch .gitignore
  ```
*Powershell:*

  ```HTML
  new-item .gitignore
  ```

  <li>Inside .gitignore file write:</li>

  ```HTML
  node_modules/
  ```
</ol>

---
---

### Probable cause if you're having trouble ignoring node_modules:

<ol>
  <li>Ensure node_modules is listed in .gitignore:</li>

  ```HTML
  echo "node_modules/" >> .gitignore
  ```

  <li>Remove node_modules from being tracked by Git:</li>

  ```HTML
  git rm -r --cached node_modules
  ```

  <li>Add .gitignore to the staging area and commit the changes:</li>

  ```HTML
  git add .gitignore
  ```

  ```HTML
  git commit -m "Update .gitignore to exclude node_modules"
  ```

  <li>Verify node_modules is now ignored:</li>

  ```HTML
  git status
  ```

</ol>
 
---
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
