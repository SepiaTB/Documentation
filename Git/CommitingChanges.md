# Basic Command lines utilization

These are some of the most used command lines.

---

## Staging Files

Locally we have the files in our workspace.  
Our changes should be added to the staging area before finally commiting the changes.  
This staging area will allow us to check and modify the changes before commiting.

### Add files / files to Staging Area

### <code> $ git add [file1] [file2] ... </code>

### Unstage staged files

### <code> $ git reset [file] </code>

### See staging area

### <code> $ git status </code>

### See files in staging area

### <code> $ git ls-files </code>

### Remove files from working directory & staging area

### <code> $ git rm FileName </code>

### Rename files from working directory & staging area

### <code> $ git mv OldFileName NewFileName </code>

---

## Commiting Changes

When Staging area is checked we can then commit the changes.

### Commit Codeline command

When using this command our core editor will open.  
We proceed to write a short description.  
"Empty line" and a Long description of the commit.

### <code> $ git commit </code>

### Commit with short message

### <code> $ git commit -m "Short message" </code>
