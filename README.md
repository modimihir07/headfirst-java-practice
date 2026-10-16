# headfirst-java-practice

Personal practice archive for Mihir Modi, second-year Computer Engineering student, working through *Head First Java*, 3rd Edition (Sierra, Bates, Gee, 2022). Contains exercise solutions, standalone programs, and study notes created while reading the book.

## What It Is Not

This repository is not a tutorial, course material, or reference guide. It does not accept contributions, issues, or pull requests. It is a single-contributor personal archive.

## Organization

The repository contains one directory per chapter and appendix:

```
chNN-chapter-name/
  ├── exercises/
  ├── programs/
  └── notes.md
```

- `exercises/`: Solutions to exercise prompts in the chapter.
- `programs/`: Standalone runnable code written while working through the chapter.
- `notes.md`: Observations, syntax notes, and points of confusion.

## Building and Running

This repository uses standard JDK 21 without build tools. Compile and execute directly from the terminal.

Example from repository root:

```bash
# Compile
javac ch01-breaking-the-surface/programs/MyFirstApp.java

# Run
java -cp ch01-breaking-the-surface/programs MyFirstApp
```

## Note on Edition and Java Version

The 3rd Edition covers Java 11 with select Java 17 features noted. This repository targets JDK 21. When modern Java features provide clearer or safer alternatives to older constructs shown in the book, modern syntax is used and documented in that chapter's `notes.md`.

## Commit Message Convention

Commits follow a single-line format without ending punctuation or emojis:

- `chNN: short description`
- `chNN/exercise: description`
- `chNN/program: description`

Example:
`ch05/program: add Sink a Startup simple version`
