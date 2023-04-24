---
name: Web Extension Feature Checklist
about: Full Range of functionality within the Pieces for Chrome Web Extensions issue
  template's purpose here.
title: "[ Tester ] Web Extension Feature Checklist "
labels: Chrome Feat CheckList
assignees: ben-at-pieces

---

## Feature Checklist: One-click save for code snippets

**One-click save:** 
- [ ] The user should be able to easily save code snippets from the web with a single click using Pieces for Developers Chrome Extension.

**Hover-and-click:** 
- [ ] The user should be able to hover over any code block on a webpage and click the Pieces button to save the code snippet.

**Keyboard shortcuts:** 
- [ ] The user should be able to use keyboard shortcuts to save code snippets with ease. (Mac: Cmd + Shift + S, Windows: Alt + Shift + S)

**Code highlighting:** 
- [ ] The user should be able to highlight and right-click to save code snippets quickly.

**Automatic snippet enrichment:** 
- [ ] Pieces should automatically enrich the saved snippets for enhanced productivity and efficiency.



## Chrome Ext: Snippet Management

**View Suggested Snippets**
- [ ] Expected Behavior: The user should be able to see a list of suggested snippets from the current webpage in the list.

**Save Suggested Snippet**
- [ ] Expected Behavior: The user should be able to save the suggested snippet successfully to Pieces.

**View Snippet History**
- [ ] Expected Behavior: The user should be able to see a list of their snippet history up to the last 100 snippets.

**Clear Snippet History**
- [ ] Expected Behavior: The user should be able to completely clear their snippet history list and the webpage should refresh.

**Filter by Last X Webs**
- [ ] Expected Behavior: The user should be able to see a subset of their snippet history based on the last X websites they've visited. This is dependent on the number set in their settings for "Number of recent sites to save snippets for."

**Filter by Last 100 Snippets**
- [ ] Expected Behavior: The user should be able to see their full history of up to 100 snippets.

**Toggle Between Tabs & Repeat**
- [ ] Expected Behavior: The user should be able to toggle between different tabs (that have been refreshed with the latest chrome extension) and the data in the popover should remain consistent.


## Chrome Extension: Snippet Management

### View Suggested Snippets
- [ ] **Test case:** Navigate to a webpage with code snippets.
- [ ] **Expected behavior:** A list of suggested snippets from the current webpage should appear in the Pieces popover.

### Save Suggested Snippet
- [ ] **Test case:** Select a suggested snippet from the list in the Pieces popover and click the save button.
- [ ] **Expected behavior:** The suggested snippet should be saved successfully to Pieces.

### View Snippet History
- [ ] **Test case:** Navigate to the Pieces popover and select "View snippet history."
- [ ] **Expected behavior:** A list of the user's snippet history, up to the last 100 snippets, should be displayed.

### Clear Snippet History
- [ ] **Test case:** Navigate to the Pieces popover and select "Clear snippet history."
- [ ] **Expected behavior:** The user's snippet history should be completely cleared and the webpage should refresh.

### Filter by Last X Websites
- [ ] **Test case:** Navigate to the Pieces popover and select "Filter by last X websites."
- [ ] **Expected behavior:** The user should be able to see a subset of their snippet history based on the last X websites they've visited. The number of websites displayed is dependent on the number set in the user's settings for "Number of recent sites to save snippets for."

### Filter by Last 100 Snippets
- [ ] **Test case:** Navigate to the Pieces popover and select "Filter by last 100 snippets."
- [ ] **Expected behavior:** The user should be able to see their full snippet

### Toggle Between Tabs and Repeat
- [ ] **Test case:** Open a webpage with code snippets and save one or more snippets to Pieces. Navigate to a different tab and then return to the original tab. Open the Pieces popover and verify that the saved snippets are still visible.
- [ ] **Expected behavior:** The user should be able to toggle between different tabs (that have been refreshed with the latest chrome extension) and the data in the popover should remain consistent.
