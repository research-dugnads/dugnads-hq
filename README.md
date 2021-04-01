# Research Dugnads HQ

A landing page for how to structure and run Research Dugnads!

**Table of Contents:**

- [Working with the Website Locally](#working-with-the-website-locally)
  - [Installing Hugo](#installing-hugo)
  - [Creating new content](#creating-new-content)
  - [Locally rendering changes](#locally-rendering-changes)
  - [Changing the theme](#changing-the-theme)
  - [Updating the theme](#updating-the-theme)

---

## Working with the Website Locally

The website is built using a tool called [Hugo](https://gohugo.io/)

### Installing Hugo

On MacOS using Homebrew, install Hugo using the following command.

```bash
brew install hugo
```

See Hugo's [Installation Guide](https://gohugo.io/getting-started/installing/) for other systems.

### Creating new content

The below command will create a new content file with the appropriate headings.

:warning: Make sure this command is run from the root of the directory.

```bash
hugo new path/to/new-content.md
```

### Locally rendering changes

To see your changes locally, run the below command and then open `localhost:1313` in your browser.

```bash
hugo server -D
```

### Changing the theme

Select a new theme from https://themes.gohugo.io/ and run the following command, updating `USERNAME` and `REPONAME` as appropriate.

```bash
git submodule add https://github.com/USERNAME/REPONAME.git theme/REPONAME
```

### Updating the theme

To pull in any upstream changes to the theme being used as a git submodule, run the following.

```bash
git submodule update --remote
```
