---
name: VS Code -Pieces OS Installation Cases/Disconnected Tests
about: This is a checklist outlining our New User Onboarding experiences and Potential
  Edge Cases
title: "[ Tester ] VS Code Pieces OS Installation/Disconnected States"
labels: VS Code Feat Checklist
assignees: akshita-lathar-pieces, ben-at-pieces

---

## Visual Studio Code
### New User 
- [ ] Pieces for VS Code is the entry point for the user 
**Expected behavior:** 
- user should be presented with the PFD readme details in a preview tab
- since this is the first experience with Pieces and the user has not yet installed POS/PFD the user should be promted with a notification letting the user know that they still need to install the platform core dependency.

### Existing User 
**Pieces OS Installed and actively running...**
User has Pieces OS & PFD installed & running in the background, then the user downloads Pieces for VS Code Extension.
- [ ] user should be able to complete all expected feature functionality within the Pieces for VS Code Extension. 
for a link to the VS Code Feature Checklist Please see the following [link](https://github.com/pieces-app/Pieces-Product-Checklists/issues/new?assignees=ben-at-pieces&labels=VS+Code+Feat+Checklist&template=vs-code-feature-checklist.md&title=%5B+Tester+%5D+VS+Code+Feature+Checklist+)

**Pieces OS Installed but not actively running...**
Situation:
_User has Pieces OS and PFD installed BUT Not running in the background, then the user downloads the Pieces for VS Code Extension._
- [ ] user presented with the following notification
![image](https://user-images.githubusercontent.com/101364072/232525094-bb541927-6c33-4320-baf7-a0621d3652a3.png)
**Clicking this link **
- [ ] user is redirected to the Pieces OS/PFD Install Page [link](https://pieces.app/)
- [ ] following the Installation steps allows user to install and sign in reflects in the Pieces Side Bar

**Vanity Domain Name** 
- [ ] does the user's vanity name appear in the 

**cloud -**
- [ ] can a user connect/disconnect from the Pieces Cloud?


## Disconnect Tests
### With the extension installed and running, close Pieces OS and...

Upon Disconnecting from Pieces OS, users should expect the following notification for all of the cases below
![image](https://user-images.githubusercontent.com/101364072/232526979-6c578b78-cc47-4155-9ef3-88757f346760.png)

If the user has not yet Installed the Pieces OS/PFD we show the following redirect notification...
![image](https://user-images.githubusercontent.com/101364072/232527436-f9e4261b-8fcd-4b52-89bf-5d929fb3f328.png)

**After Installation, the follwoing action should not fail or present a redirect notification... In the cases below we will be purposefully disconnecting from Pieces OS.** 

**If on MacOS**, locate the Pieces OS Icon in the system trey (top bar) and quit the application. (selecting the x in the GUI only minimizes the window)

**If on Windows**, locate the Pieces OS Icon in the system trey (lower righthand side of the window) and quit the application. _(selecting the x in the GUI only minimizes the window)_

#### case 1: Saved Snippets
- [x] saved snippets successfully refreshes after reconnecting to Pieces OS?  (should be automatic)
- [ ] Right Click Save to Pieces... successfully saved to Pieces after reconnecting to Pieces OS?
- [ ] Keyboard Shortcut Save to Pieces... Successfully saved to Pieces after reconnecting to Pieces OS

#### case 2: Suggested Snippets
- [ ] suggested snippets successfully refreshes after reconnecting to Pieces OS?  (should be automatic)


#### case 3: Explored Materials & Snippet Insights
- [ ] explored materials successfully refresh after reconnecting to Pieces OS?  (should be automatic)
- [ ] does the "Explored Materials and Snippet Insights side bar menu item expand after making the selection?

#### case 4: Related Materials to current selection
- [ ] right click "Find Related Materials" shows the following success notification & redirect
![image](https://user-images.githubusercontent.com/101364072/232550141-b778316d-8c3d-4018-a9d6-9c5d572e3c1d.png)
- [ ] clicking "view" shows the related materials in the sidebar dropdown?
- [ ] the expanded side bar menu shows snippets related to the current selection?
- [ ] related materials refreshes after successfully reconnecting to Pieces OS?  (should be automatic)


#### case 5:  Shareable link
- [] snippet is saved to pieces prior to generating the shareable link?
- [] successfully generate shareable link after reconnected to Pieces OS? (should be automatic)
![image](https://user-images.githubusercontent.com/101364072/232550761-ffe87bf5-4871-444f-bb19-ba7ad3daba3e.png)

#### case 6: Save to Pieces 
- [] snippet is saved to Pieces after reconecting to Pieces OS (should be automatic)
