## Commands
- git fetch
- git pull
- git push
---

### Fetch

- Basic usage
  ```
  git fetch
  ```
- Specific
  - Remote
    ```
    git fetch origin
    ```
  - Branch
    ```
    git fetch origin dev-master
    ```
- All remotes
  ```
  git fetch --all
  ```
- Tags
  ```
  git fetch -t
  ```
- Prune
  - Unuse branch
    ```
    git fetch -p
    ```
  - Tag
    ```
    git fetch -p -P
    ```
- Optional
  ```
  git fetch origin main --set-upstream
  ```
---

### Pull
- Remote branch
  ```
  git pull origin main
  ```
- Rebase
  ```
  git pull -r origin main
  ```
- No fast-forward
  ```
  git pull --no-ff origin main
  ```
- Allow unrelated history
  ```
  git pull origin main --allow-unrelated-histories
  ```
---

### Push
- All branch
  ```
  git push --all
  ```
- Specific
  ```
  git push origin dev
  ```
- Different remote branch
  ```
  git push origin dev:develop
  ```
- Delete branch
  ```
  git push origin -d dev
  ```
- Push tags
  - All tags
    ```
    git push --tags
    ```
  - Specific
    ```
    git push origin 1.0.0
    ```
  - Delete
    ```
    git push origin -d 1.0.0
    ```
- Optional
  ```
  git push -u origin dev
  ```
---