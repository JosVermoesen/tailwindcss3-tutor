# Tailwindcss version 3 Turtor

## About Tailwind CSS commands

```bash
npm install tailwindcss
```

After installing Tailwind CSS, you can run the command in your terminal:

```bash
npx tailwindcss -i ./src/css/input.css -o ./src/css/output.css --watch
```

The `-i` flag specifies the input file, and the `-o` flag specifies the output file. This command is typically run in a terminal or command prompt where Tailwind CSS is installed.

This command initializes Tailwind CSS and processes the specified input CSS file, applying Tailwind's utility classes and generating the output CSS file. The `--watch` flag allows Tailwind to watch for changes in the input file and automatically recompile the output file whenever changes are detected.

```bash
npm run dev
```

This command is typically used in a Node.js project to start a development server or run a development build process. The specific behavior of `npm run dev` depends on the scripts defined in your project's `package.json` file.

### Upgrading Tailwind CSS

You need to install the Tailwind CLI tool to use the upgrade command:

```bash
npm install tailwindcss @tailwindcss/cli
```

This command installs Tailwind CSS and the Tailwind CLI tool as development dependencies in your Node.js project. The `@tailwindcss/cli` package provides a command-line interface for processing Tailwind CSS files.

```bash
npx @tailwindcss/upgrade
```

This command is used to upgrade Tailwind CSS to the latest version. It checks for updates and applies them to your project, ensuring you have the latest features and fixes.

## About Git commands

Git is a version control system that allows you to track changes in your codebase, collaborate with others, and manage different versions of your project. It is widely used in software development for its powerful branching and merging capabilities.

```bash
git init
```

This command initializes a new Git repository in the current directory. It creates a `.git` subdirectory that contains all the necessary files for version control.

```bash
git status
```

This command shows the current status of your Git repository. It displays which files are staged for commit, which files have changes that are not staged, and which files are untracked (not added to the repository).

```bash
git add .
```

This command stages all changes in the current directory and its subdirectories for the next commit. The `.` means "all files in the current directory." You can also specify individual files or directories instead of using `.`.

```bash
git commit -m "Initial commit"
```

This command creates a new commit with the staged changes. The `-m` flag allows you to provide a commit message directly in the command line. The message should describe the changes made in this commit.

```bash
git branch
```

This command lists all the branches in your Git repository. The current branch will be highlighted with an asterisk (`*`). Branches are used to work on different features or fixes in isolation from the main codebase.

```bash
git checkout -b new-branch
```

This command creates a new branch named `new-branch` and switches to it. The `-b` flag indicates that you want to create a new branch. This is useful for starting work on a new feature or bug fix without affecting the main branch.

```bash
git push origin new-branch
```

This command pushes the `new-branch` to the remote repository named `origin`. The `origin` is the default name for the remote repository you cloned from or set up. This command makes your new branch available to others and allows them to collaborate on it.

## Project Files

### Version 3

[version3]

### Version 3 upgrade

[version3update]

### Version 4

[version4]

[version3]: https://github.com/emmanuelbakare/Mastering-Tailwind-CSS-with-Project-Examples
[version3update]: https://github.com/emmanuelbakare/Tailwind-CSS-V4-Start-to-Mastery-18-Project-Examples
[version4]: https://github.com/emmanuelbakare/Tailwind-CSS-V4-Start-to-Mastery-18-Project-Examples
