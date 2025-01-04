## Removing Branches

### Locally :
ex to delete dev branch:

```bash
git branch dev
```

### Remotly :

```
git push origin --delete dev

```

## Tags in Git

### Annotated Tags:
- Include metadata (author, date, message).
- Useful for official releases.
- Created with:

  ```bash
  git tag -a <tag-name> -m "Message"

  ```

  #### Lightweight Tags:
  ###### Simple pointers to a commit.
  ###### Do not include metadata.
  ###### created with :

    ```bash

    git tag <tag-name>


    ```

#### When to Use Rebase:

Clean Commit History: Use rebase to organize commits before merging.
Avoid Merge Commits: Use rebase for linear history.

```bash

git rebase <branch-name>

```

## Listing Tags

Use the following command to list tags:
```bash

git tag

```

## Deleting Tags
#### Locally:

```bash

git tag -d <tag-name>

```

#### Remotly:

```bash

git push origin --delete <tag-name>

```

<div>
<img src="https://github.com/user-attachments/assets/021fa8c2-351a-4873-9726-7c47fd9a625c" width="200">
<img src="https://github.com/user-attachments/assets/021fa8c2-351a-4873-9726-7c47fd9a625c" width="200">
</div>






