# What are Flags?

Flags are special options that are used with terminal commands to change or control how a command behaves.

A flag usually starts with a hyphen (`-`) or double hyphen (`--`).

---

## Why Do We Use Flags?

Flags allow us to modify the default behavior of a command.

The same command can perform different actions depending on the flag used with it.

---

## 1. Single Dash Flag

A single-character flag usually starts with one hyphen (`-`).

### Example

`ls -l`

Here:

- `ls` is the command.
- `-l` is the flag.

The `-l` flag displays the contents in a detailed or long format.

---

## 2. Multiple Flags

Multiple flags can sometimes be used together.

### Example

`ls -la`

Here:

- `-l` → displays detailed information.
- `-a` → includes hidden files and directories.

So `ls -la` displays files and directories, including hidden ones, in detailed format.

---

## 3. Long-Form Flags

Some commands use a double hyphen (`--`) for longer, more descriptive options.

### Example

`command --help`

The `--help` option is commonly used to display information about how a command can be used.

---

## 4. Flags vs Arguments

A **flag** changes how a command behaves, while an **argument** provides information or a value to the command.

### Example

`ls -l projects`

Here:

- `ls` → command
- `-l` → flag
- `projects` → argument

The command lists the contents of the `projects` directory in long format.

---

## Important Points

- Flags are used to modify the behavior of commands.
- Short flags generally use a single hyphen (`-`).
- Long-form options generally use two hyphens (`--`).
- Multiple flags can sometimes be combined.
- A flag and an argument are not the same thing.
- The available flags depend on the command being used.

---

## Quick Revision

| Term | Meaning |
|------|---------|
| Command | Tells the terminal what action to perform |
| Flag | Changes or controls the behavior of a command |
| Argument | Provides information or a value to the command |
| `-` | Commonly used before short flags |
| `--` | Commonly used before long-form options |

### Example

`ls -la projects`

- `ls` → Command
- `-la` → Flags
- `projects` → Argument