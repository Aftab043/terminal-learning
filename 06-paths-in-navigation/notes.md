# Paths in Navigation

A path is the location or address of a file or directory in the file system.

Paths are mainly of two types:

- Absolute Path
- Relative Path

---

## 1. Absolute Path

An **absolute path** gives the complete location of a file or directory.

It starts from the root or starting point of the file system and provides the complete address.

### Example

`C:\Users\Aftab\Desktop\terminal-learning`

This is an absolute path because it gives the complete location of the `terminal-learning` directory.

### Key Point

An absolute path does not depend on the current directory.

---

## 2. Relative Path

A **relative path** specifies the location of a file or directory relative to the current working directory.

### Example

Suppose the current directory is:

`terminal-learning`

And inside it there is a directory:

`06-paths-in-navigation`

We can navigate to it using:

`cd 06-paths-in-navigation`

This is a relative path because the path is given from the current location.

### Key Point

A relative path depends on the current working directory.

---

## 3. Current Directory (.)

`.` represents the **current directory**.

It refers to the directory in which we are currently working.

### Example

`cd .`

This means staying in the current directory.

### Key Point

`.` is used to represent the current location.

---

## 4. Parent Directory (..)

`..` represents the **parent directory** of the current directory.

It is used to move one level up in the directory structure.

### Example

Suppose the current location is:

`terminal-learning/06-paths-in-navigation`

Using:

`cd ..`

will move us to:

`terminal-learning`

### Key Point

`..` always refers to the directory one level above the current directory.

---

## Absolute Path vs Relative Path

| Type | Meaning |
|------|---------|
| Absolute Path | Gives the complete location |
| Relative Path | Gives the location relative to the current directory |

### Example

Absolute Path:

`C:\Users\Aftab\Desktop\terminal-learning\06-paths-in-navigation`

Relative Path:

`06-paths-in-navigation`

---

## Important Symbols

| Symbol | Meaning |
|--------|---------|
| `.` | Current directory |
| `..` | Parent directory |
| `/` | Root directory |

---

## Quick Revision

- A **path** tells us the location of a file or directory.
- An **absolute path** gives the complete location.
- A **relative path** is based on the current working directory.
- `.` represents the current directory.
- `..` represents the parent directory.
- Relative paths are useful for navigating from the current location.
- Absolute paths provide the complete address of a location.