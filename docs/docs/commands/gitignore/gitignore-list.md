---
title: "gh-templates gitignore list"
sidebar_label: "gitignore list"
---

# List Gitignore Templates

List all available gitignore templates that can be added to your repository. Templates are sourced from [github/gitignore](https://github.com/github/gitignore).

## Usage

```bash
gh-templates gitignore list
```

## Options

| Option               | Description                        |
|----------------------|------------------------------------|
| `-p, --popular`      | Show popular templates             |
| `-g, --global`       | Show global templates              |
| `-c, --community`    | Show community templates           |
| `--update-cache`     | Update the gitignore cache         |
| `-h, --help`         | Print help                         |

## Examples

### List All Available Templates

```bash
gh-templates gitignore list
```

### List Only Popular Templates

```bash
gh-templates gitignore list --popular
```

### List Global Templates

```bash
gh-templates gitignore list --global
```

### List Community Templates

```bash
gh-templates gitignore list --community
```

### Update the Template Cache

```bash
gh-templates gitignore list --update-cache
```

## Sample Output

```text
✓ Available gitignore templates:

POPULAR
   > actionscript         (Actionscript.gitignore)
   > ada                  (Ada.gitignore)
   > adventuregamestudio  (AdventureGameStudio.gitignore)
   > agda                 (Agda.gitignore)
   > al                   (AL.gitignore)
   > android              (Android.gitignore)
   > angular              (Angular.gitignore)
   > appceleratortitanium (AppceleratorTitanium.gitignore)
   > appengine            (AppEngine.gitignore)
   > archlinuxpackages    (ArchLinuxPackages.gitignore)
   > autotools            (Autotools.gitignore)
   > ballerina            (Ballerina.gitignore)
   > c                    (C.gitignore)
   > c++                  (C++.gitignore)
```

## Gitignore Template Categories

GitHub's `gitignore` repository organizes templates into several categories:

- **Popular** (root folder):  
  These are the most commonly used `.gitignore` templates, found directly in the root of the repository. They cover widely-used languages, frameworks, and tools.

- **Community** (`/community` folder):  
  Templates contributed and maintained by the community for more specialized or less common technologies. These may be less frequently updated but are valuable for niche use cases.

- **Global** (`/global` folder):  
  Templates intended for global use across all repositories on a developer's machine. These typically ignore files generated by operating systems or editors (e.g., macOS, Windows, Vim, Emacs).

Use the template that best matches your project's needs. For most projects, start with a popular template and supplement with community or global

## Related Commands

- [Preview Gitignore Templates](./gitignore-preview.md) - Preview template content
- [Add Gitignore Templates](./gitignore-add.md) - Add templates to your repository
