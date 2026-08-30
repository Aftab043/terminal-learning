# Making Directories

A directory is a folder used to store and organize files and other directories.

In the terminal, we can create directories using the `mkdir` command.

---

## 1. mkdir

`mkdir` stands for **Make Directory**.

It is used to create a new directory.

### Syntax

`mkdir directory-name`

### Example

`mkdir projects`

This creates a new directory named `projects`.

---

## 2. Creating Multiple Directories

We can create more than one directory with a single `mkdir` command.

### Example

`mkdir html css javascript`

This creates three directories:

- `html`
- `css`
- `javascript`

---

## 3. Creating a Directory with Spaces

If the directory name contains spaces, enclose the name in quotes.

### Example

`mkdir "my projects"`

This creates a directory named `my projects`.

---

## 4. Creating Nested Directories

A directory can contain another directory.

For example, we may want to create:

`projects/web`

Using:

`mkdir -p projects/web`

This creates the `projects` directory and the `web` directory inside it if they do not already exist.

---

## 5. Checking the Created Directory

After creating a directory, we can use the `ls` command to check whether it was created.

### Example

`mkdir practice`

`ls`

If `practice` appears in the output, the directory was created successfully.

---

## Important Points

- `mkdir` stands for **Make Directory**.
- It is used to create new directories.
- Multiple directories can be created with one command.
- Use quotes when a directory name contains spaces.
- The `-p` option can be used to create parent directories along with nested directories.
- Use `ls` to check the contents of the current directory.

---

## Quick Revision

| Command | Purpose |
|---------|---------|
| `mkdir folder` | Creates a directory |
| `mkdir one two three` | Creates multiple directories |
| `mkdir "my folder"` | Creates a directory with spaces |
| `mkdir -p parent/child` | Creates nested directories |
| `ls` | Checks the created directory |