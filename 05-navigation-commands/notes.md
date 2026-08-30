# Navigation Commands

Navigation commands are used to move from one directory to another in the file system.

They help us change our current location and navigate through different folders.

---

## 1. cd

`cd` stands for **Change Directory**.

It is used to move from the current directory to another directory.

### Syntax

`cd directory-name`

### Example

`cd projects`

This moves us into the `projects` directory.

### Key Point

`cd` is the main command used for navigating between directories.

---

## 2. cd ..

`cd ..` is used to move **one level back** to the parent directory.

### Syntax

`cd ..`

### Example

Suppose we are currently inside:

`projects/javascript`

Using:

`cd ..`

will move us to:

`projects`

### Key Point

`..` represents the **parent directory**.

---

## 3. cd /

`cd /` is used to move to the **root directory**.

### Syntax

`cd /`

### Key Point

The root directory is the top-level directory of the file system.

---

## 4. cd ~

`cd ~` is used to move to the **home directory** of the current user.

### Syntax

`cd ~`

### Key Point

The `~` symbol represents the user's home directory.

---

## 5. cd -

`cd -` is used to move back to the **previous working directory**.

### Syntax

`cd -`

### Example

If we move from:

`/projects`

to:

`/projects/javascript`

and then use:

`cd -`

we return to:

`/projects`

### Key Point

`cd -` is useful when switching between two recently used directories.

---

# Navigation with Paths

We can also provide a path with the `cd` command to navigate directly to a specific location.

### Example

`cd projects/javascript`

This moves into the `javascript` directory inside the `projects` directory.

---

# Absolute Path

An absolute path starts from the root directory and provides the complete location of a file or directory.

### Example

`cd /c/Users/Aftab/terminal-learning`

It specifies the complete path to the `terminal-learning` directory.

---

# Relative Path

A relative path specifies a location based on the current working directory.

### Example

`cd projects`

This works when the `projects` directory exists inside the current directory.

---

# Quick Revision

| Command | Purpose |
|---------|---------|
| `cd folder-name` | Moves into a directory |
| `cd ..` | Moves to the parent directory |
| `cd /` | Moves to the root directory |
| `cd ~` | Moves to the home directory |
| `cd -` | Moves to the previous directory |

---

# Important Points

- `cd` → Changes the current directory.
- `..` → Represents the parent directory.
- `/` → Represents the root directory.
- `~` → Represents the home directory.
- `-` → Represents the previous working directory.
- An **absolute path** gives the complete location.
- A **relative path** gives a location relative to the current directory.