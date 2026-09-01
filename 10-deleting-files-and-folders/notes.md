# Deleting Files & Folders

Files and directories can be deleted directly from the terminal using commands.

The main command used for deleting files and directories is `rm`.

---

## 1. Deleting a File

The `rm` command is used to remove a file.

### Syntax

`rm file-name`

### Example

`rm notes.txt`

This deletes the `notes.txt` file from the current directory.

---

## 2. Deleting Multiple Files

We can delete multiple files using a single `rm` command.

### Example

`rm file1.txt file2.txt file3.txt`

This removes all three specified files.

---

## 3. Deleting an Empty Directory

The `rmdir` command is used to remove an empty directory.

### Syntax

`rmdir directory-name`

### Example

`rmdir practice`

This removes the `practice` directory if it is empty.

---

## 4. Deleting a Directory with Files

The `rm -r` command is used to remove a directory along with the files and subdirectories inside it.

### Syntax

`rm -r directory-name`

### Example

`rm -r projects`

This removes the `projects` directory and its contents.

---

## 5. Force Delete

The `-f` flag can be used with `rm` to force the removal without asking for confirmation.

### Example

`rm -f notes.txt`

This forcefully removes the specified file.

---

## 6. Delete a Directory Recursively and Forcefully

The `-rf` options can be used together to recursively and forcefully remove a directory and its contents.

### Example

`rm -rf projects`

This removes the `projects` directory, including all files and subdirectories inside it, without asking for confirmation.

### Important Warning

Be extremely careful with `rm -rf`.

Deleted files and folders may not be moved to the Recycle Bin and can be difficult or impossible to recover.

---

## 7. Checking Before Deleting

It is a good practice to check the contents of the current directory before deleting anything.

### Example

`ls`

After checking the files and directories, use the appropriate deletion command.

---

# Important Points

- `rm` → removes files.
- `rm file.txt` → deletes a specific file.
- `rm file1.txt file2.txt` → deletes multiple files.
- `rmdir` → removes an empty directory.
- `rm -r` → removes a directory and its contents recursively.
- `rm -f` → forcefully removes a file.
- `rm -rf` → recursively and forcefully removes a directory and its contents.
- Always check the file or directory name before using a delete command.
- Be especially careful with `rm -rf` because deletion can be irreversible.

---

# Quick Revision

| Command | Purpose |
|---------|---------|
| `rm file.txt` | Deletes a file |
| `rm file1.txt file2.txt` | Deletes multiple files |
| `rmdir folder` | Deletes an empty directory |
| `rm -r folder` | Deletes a directory and its contents |
| `rm -f file.txt` | Forcefully deletes a file |
| `rm -rf folder` | Forcefully deletes a directory and its contents |

---

# Example

Suppose we have:

`projects/`

Inside it:

`index.html`
`style.css`

To delete the entire `projects` directory and its contents:

`rm -r projects`

After deletion, the `projects` directory and its contents will be removed.