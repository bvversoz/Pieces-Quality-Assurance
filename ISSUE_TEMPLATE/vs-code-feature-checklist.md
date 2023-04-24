---
name: VS Code Feature Checklist
about: Full Range of Feature Functionality within the Pieces for VS Code Extension
title: "[ Tester ] VS Code Feature Checklist "
labels: VS Code Feat Checklist
assignees: ben-at-pieces

---

- [ ] ### Pieces Explorer 
      The explorer appears in the primary sidebar. 

- [ ] ### Saved Pieces Tree View 
      - The Tree View collapses when the arrow to the left of the Title is clicked.
      - Pieces are listed by language classification.
      - Pieces reflect the current state of the local os_server database.
      - Expanding an arbitrary language classification presents at least one Piece.
      - Clicking on said Piece opens a new tab in the editor.
      - The new tab opens with the title of the Piece.
      - The Piece can be selected and copied.

- [ ] ### Add Links 
      - Presents a dialogue for entering a link for the Piece.
      - Provides a “Link added successfully” notification in the editor when entered.
      - The link is reflected in PFD.

- [ ] ### Add Tags 
      - Presents a dialogue for entering tags for the Piece.
      - Provides a “Tag added successfully” notification in the editor when entered.
      - The tag is reflected in PFD.

- [ ] ### Delete 
      - Provides a “Snippet successfully deleted” notification in the editor when clicked.
      - Removes the Piece from the Tree View.
      - Removes the Piece from PFD.

- [ ] ### Edit 
      - Opens a new tab with the Piece contents.
      - Allows the user to edit the content of the Piece.
      - When edited, saving the Piece triggers the new tab to close.
      - Notifies the user that the Piece was successfully edited.
      - The edited Piece is reflected in PFD.

- [ ] ### Insert Snippet 
      - When editing an arbitrary file, clicking “Insert Snippet” inserts the Piece.
      - With the cursor in an arbitrary position with no selection, the Piece is inserted.
      - With the cursor in an arbitrary position with a selection, the Piece is inserted and replaces the selection.
      - The undo command reverts the file prior to the insertion.

- [ ] ### Reclassify 
      - Opens a menu that allows the user to reclassify the Piece.
      - Provides a notification when the user reclassifies.
      - The reclassification is reflected in PFD.

- [ ] ### Rename 
      - Presents a dialogue for entering a new name for the Piece.
      - Provides a “snippet successfully renamed” notification in the editor when entered.
      - The rename is reflected in PFD.

- [ ] ### Share via Pieces Link 
      - Connects the user to the cloud, if they have not done so.
      - Notifies via the editor the shareable link has been generated successfully.
      - Presents a “Copy to Clipboard” button inside of the notification if- [ ] ### Import User Snippets to Pieces 
      Import user snippets to Pieces for use in your projects.

- [ ] ### Pieces: Autocomplete 
      Enable autocomplete for Pieces snippets.

- [ ] ### Pieces: Autocomplete Key 
      Customize the key used to trigger autocomplete.

- [ ] ### Pieces: Auto Expansion 
      Automatically expand snippets based on the active file extension.

- [ ] ### Pieces: Automatically Copy Link 
      Automatically copy generated link to clipboard when sharing a snippet.

- [ ] ### Pieces: Auto Save 
      Enable auto-save for snippets and materials.

- [ ] ### Pieces: Cloud Capabilities 
      Configure cloud capabilities, including cloud sync and backup.

- [ ] ### Pieces: Display Name 
      Customize the display name for Pieces in the VS Code explorer.

### Pieces » Explored Snippet Insights: Delete All 
- [ ] Delete all explored materials and snippet insights.

### Pieces » Explored Snippet Insights: Document With Pieces Insights 
- [ ] Insert the description from an explored snippet as a comment above the code.

### Pieces » Explored Snippet Insights: Explore And Save
- [ ] Automatically save explored snippets and material insights.

## Pieces Settings

- [ ] ### Import User Snippets to Pieces
      Import user snippets to Pieces for use in your projects.

- [ ] ### Pieces: Autocomplete
      Enable autocomplete for Pieces snippets.

- [ ] ### Pieces: Autocomplete Key
      Customize the key used to trigger autocomplete.

- [ ] ### Pieces: Auto Expansion
      Automatically expand snippets based on the active file extension.

- [ ] ### Pieces: Automatically Copy Link
      Automatically copy generated link to clipboard when sharing a snippet.

- [ ] ### Pieces: Auto Save
      Enable auto-save for snippets and materials.

- [ ] ### Pieces: Cloud Capabilities
      Configure cloud capabilities, including cloud sync and backup.

- [ ] ### Pieces: Display Name
      Customize the display name for Pieces in the VS Code explorer.

- [ ] ### Pieces » Explored Snippet Insights: Delete All
      Delete all explored materials and snippet insights.

- [ ] ### Pieces » Explored Snippet Insights: Document With Pieces Insights
      Insert the description from an explored snippet as a comment above the code.

- [ ] ### Pieces » Explored Snippet Insights: Explore And Save
      Automatically save explored snippets and material insights.

- [ ] ### Pieces: Launch Pieces OS
      Launch Pieces OS from within VS Code.
