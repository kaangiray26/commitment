# commitment
Configure commit messages individually

## How-To
```
1. List all staged files:
   git diff --cached --name-only --oneline > list

2. Open a nano file with the following content and wait for the user to enter individual commit messages:
   dir/file1 This is a commit message
   dir/file2 This is another commit message
   #dir/file3 This line will be ignored not committed


3. Iterate the files on the list with a proper commit message and push them to the repo:
   git commit -m "<commit message>" <file-path>
   git push
```