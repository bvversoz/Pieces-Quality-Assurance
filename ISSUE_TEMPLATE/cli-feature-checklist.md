---
name: CLI Feature Checklist
about: Full Range of Feature Functionality within the Pieces CLI
title: "[Tester ] CLI Feature CheckList"
labels: PFD Feat Checklist, Pieces CLI Feat CheckList
assignees: ben-at-pieces

---

# Checklist

## Installation

### Requirements

Before installing Pieces CLI, you must have the following installed on your machine:

- [Homebrew](https://brew.sh/)

## Installing Pieces CLI

To install Pieces CLI, run the following commands:
bash
$ brew tap pieces-app/pieces
$ brew install pieces
Typing `pieces` into the terminal results in the CLI being invoked with usage information



After installation, typing `pieces` into the terminal results in the CLI being invoked with usage information.

## Commands

- [ ] **pieces create:** opens the user's selected terminal editor.
- [ ] **pieces edit:** displays a user's most recent snippets, along with the classification and preview.
- [ ] **pieces install:** installs Pieces OS and Pieces for Developers. (Note: requires elevated privileges.)
- [ ] **pieces list history:** prints the 10 most recent entries from the user’s shell history file.
- [ ] **pieces list settings:** prints the user’s current CLI settings.
- [ ] **pieces list snippets:** prints the user’s most recent snippets, analogous to the pieces edit snippet menu.
- [ ] **pieces save .:** saves the clipboard content as a Piece, reflecting it in PFD.
- [ ] **pieces save clipboard:** saves the clipboard content as a Piece, reflecting it in PFD and printing the clipboard text to the user.
- [ ] **pieces save history:** prints the 10 most recent entries from the shell history and prompts the user to select the ones they wish to save.
- [ ] **pieces snippet-types:** prints the valid snippet types.
- [ ] **pieces tutorial:** guides the user through creating and using a new snippet.
- [ ] **pieces use:** prompts the user to select a snippet to copy to their clipboard.

Note: Some commands require elevated privileges, such as `pieces install`.

For more information on each command and its usage, use the `-h` or `--help` flag. For example, to get help with the `pieces create` command, run:
