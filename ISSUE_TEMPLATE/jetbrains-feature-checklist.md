---
name: JetBrains Feature CheckList
about: " Full Range of Feature Functionality within the Pieces for JetBrains"
title: "[ Tester ] JetBrains Feature Checklist "
labels: Chrome Feat CheckList, JetBrains Feat CheckList
assignees: ben-at-pieces

---

## Pieces for JetBrains Feature Manual Testing Checklist

### Installation:

- [ ] Install Pieces OS and the Pieces app from [here](https://code.pieces.app/install).
- [ ] Install Pieces for IntelliJ through the JetBrains marketplace, from the Pieces site, or from inside the IntelliJ app by going to Preferences > Plugins and searching for Pieces.

### Saving Snippets and Files to Pieces from IntelliJ:

- [ ] Highlight the snippet or file and save it to Pieces using the keyboard shortcut (Windows: CTRL + P twice, Mac: ⌘⌥P) or by right-clicking and selecting "Save to Pieces."

### Context that’s automatically captured when saving to Pieces from IntelliJ:

- [ ] Pieces captures information like a snippet’s source and tags it to make it simple to find later on.

### Suggested Save:

- [ ] Pieces can intelligently identify and save snippets based on re-use patterns in your workflow in JetBrains.
- [ ] To opt-out of Suggested Save, go to Preferences > Tools > Pieces and click on Suggested Save.

### Viewing Saved Snippets:

- [ ] Right-click in your code and select “My Saved Pieces” to view your saved snippets in IntelliJ.
- [ ] Refresh your saved Pieces in your IDE by right-clicking in your code and selecting “Refresh Saved Pieces.”
- [ ] View your saved snippets inside IntelliJ via the right-click menu or from the Tools menu.
- [ ] Insert a saved snippet to your cursor position via the right-click menu or from the Tools menu.



### Search for Snippets
- [ ] Verify opening a search dialogue allowing the user to search for code snippets
- [ ] Verify search functionality

### Open Snippet
- [ ] Verify opening the selected code snippet in a new editor tab
- [ ] Verify opening multiple snippets simultaneously

### Save Snippet
- [ ] Verify saving the currently selected code as a new snippet to the Pieces OS
- [ ] Verify giving a unique name for a saved snippet

### Rename Snippet
- [ ] Verify renaming a selected code snippet
- [ ] Verify ensuring that the renamed snippet is updated in the Pieces OS

### Reclassify Snippet
- [ ] Verify changing the classification of a selected code snippet
- [ ] Verify ensuring that the reclassified snippet is updated in the Pieces OS

### Edit Snippet Description
- [ ] Verify editing the description of a selected code snippet
- [ ] Verify ensuring that the edited description is updated in the Pieces OS

### Delete Snippet
- [ ] Verify deleting a selected code snippet
- [ ] Verify ensuring that the deleted snippet is removed from the Pieces OS

### Share via Pieces Link
- [ ] Verify generating a shareable link for a selected code snippet
- [ ] Verify ensuring that the generated link is copied to the clipboard

### Insert Snippet at Caret Position
- [ ] Verify inserting a selected code snippet at the current caret position
- [ ] Verify ensuring that the inserted snippet is saved to the Pieces OS

### Toggle Classification Expansion
- [ ] Verify expanding and collapsing a classification in the sidebar

### Open Snippet in Markdown Preview
- [ ] Verify opening the selected snippet in a Markdown preview

### Insert Snippet at Current Cursor Position
- [ ] Verify inserting the selected snippet at the current cursor position

### Open Snippet and Copy it to Clipboard
- [ ] Verify opening the selected snippet and copying it to the clipboard

### Copy Snippet Directly to Clipboard
- [ ] Verify copying the selected snippet directly to the clipboard

### Cloud Capabilities
- [ ] Verify using cloud resources to enrich your snippets and generate material insights
- [ ] Verify using offline/on-device capabilities to enrich your snippets and generate material insights
- [ ] Verify using a blend of cloud and local capabilities to enrich your snippets and generate material insights

### Explored Snippet Insights
- [ ] Verify inserting description results from explore snippet insights as a comment above the snippet
- [ ] Verify automatically saving explored snippets and material insights
- [ ] Verify automatically deleting explored material when manually saving to Pieces

### Insights Storage Preference
- [ ] Verify using a shared location to store insights
- [ ] Verify keeping insights within JetBrains

### GIT Integration
- [ ] Verify adding commit authors using Git history when saving a snippet
- [ ] Verify adding commit links using Git history when saving a snippet
- [ ] Verify adding tags using Git history when saving a snippet
- [ ] Verify adding commit messages from Git history to description when saving a snippet

### Sharing
- [ ] Verify automatically copying a shareable link to your clipboard once it's ready

### Assistive Mechanisms
- [ ] Verify enabling autosave
- [ ] Verify enabling autocomplete
- [ ] Verify automatically saving code selection used to find related materials if none are found

### Filter Snippet Based on the Files Extension
- [ ] Verify showing all snippets regardless of the context
    - Description: Verify that all snippets are displayed in the Pieces sidebar regardless of the file type of the currently open document.
- [ ] Verify showing snippets with unsupported types and plain text
    - Description: Verify that the Pieces sidebar displays snippets with unsupported file types and plain text.
- [ ] Verify showing only the snippets classified as the current file's type
    - Description: Verify that only the snippets classified as the current file's type are displayed in the Pieces sidebar.
