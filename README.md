# Teknasyon Git Commits Style Guidelines

## Introduction

This style guide serves as the official guide we follow in Teknasyon projects. Teknasyon is a large company with many great and diverse developers, there are many opinions on the "ideal" style in the world of development. A unified agreed-on guideline will help us collaborate together, understand and appreciate each other’s work easily :)

## Commit Types

The commit title consists of the type of the message and subject. The type is contained within the title and can be one of these types:

* **[init]** initial commits, like creating a new project
* **[feat]** add new feature
* **[fix]**  fix a bug
* **[docs]** make changes to documentation
* **[style]** update formatting, missing semi colons, etc; no code change
* **[refactor]** refactoring code
* **[test]** adding tests, refactoring test; no production code change
* **[chore]** updating build tasks, package manager configs, etc; no production code change
* **[release]** release a new version of the project


## The Subject

Subjects should be no greater than 50 characters, should **begin with a capital letter** and **do not end with a period**.

Use an imperative tone to describe what a commit does, rather than what it did. For example, **use change; not changed or changes**.

---

## Examples

- [init] Add initial project files
- [fix] Fix a bug where login button was not working
- [chore] Update dependencies
- [doc] Add README file
- [refactor] Refactor localization code
- [release] v1.0.2
