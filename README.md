# MyJavaProject

This is a simple Java project for the Git lab assignment.

## What this project includes

- `HelloWorld.java`: a simple Java program that prints `Hello, Git!`
- `.gitignore`: ignores compiled Java files and common temporary files
- `.env`: simple project environment variables
- `.vscode/tasks.json`: VS Code tasks to compile and run the Java file

## How to run in VS Code

1. Open this folder in VS Code.
2. Open `HelloWorld.java`.
3. Use Terminal → New Terminal.
4. Compile:

```bash
javac HelloWorld.java
```

5. Run:

```bash
java HelloWorld
```

Expected output:

```text
Hello, Git!
```

## Git commands used for the assignment

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --list
git init
git add HelloWorld.java
git commit -m "Initial commit with HelloWorld.java"
git status
```

This ZIP already contains a Git repository with the first commit created. You can still run `git status` to show the repository status.
