---
name: JetBrains -POS Installation Cases/Disconnected Tests
about: This is a checklist outlining our New User Onboarding experiences and Potential
  Disconnect cases
title: "[ Tester ] JetBrains New User & Disconnected Testing"
labels: JetBrains Feat CheckList
assignees: ben-at-pieces

---

## JetBrains IntelliJ
### Case 1: New User 
_User has **Pieces OS and PFD installed** and **Not running** in the background, then the user downloads the Pieces for JetBrains Plugin_
- [ ] Pieces for JetBrains is the entry point for the user 

- [ ] user presented with the following redirect?

- [ ] Pieces OS Download [Link](https://code.pieces.app/errors/need-os/jetbrains?ide=IntelliJ&ideRelease=2023.1&pluginVersion=5.2.0)

![Screenshot 2023-04-18 at 10 21 14 AM](https://user-images.githubusercontent.com/101364072/232807019-f88f6b5b-5d05-47a8-9a71-c1b4d65fd3fe.png)

**Onboarding**
![Untitled (1)](https://user-images.githubusercontent.com/101364072/232826176-feafc1fb-bdeb-4cf5-ae34-1861bc699218.png)

**Clicking this link**
- [x] following the redirect, were you able to successfully install Pieces OS?
-_as it stands, this only installs Pieces OS_

**Vanity Domain Name** 
- [x] does the user's vanity name appear in the Pieces Side Bar?
-not currently in place but seen in VS Code's Side Bar
-no method to update in settings

**Cloud**
- [x] can a user connect/disconnect from the Pieces Cloud?
-not currently in place but seen in VS Code's Side Bar

**Expected behavior:** 
- user should be presented with the PFD readme details in a preview tab
- since this is the first experience with Pieces and the user has not yet installed POS/PFD the user should be promted with a notification letting the user know that they still need to install the platform core dependency (Pieces OS).


### Existing User 
**Pieces OS Installed and actively running...**
User has Pieces OS & PFD installed & running in the background, then the user downloads Pieces forJetBrains Plugin.
- [ ] user should be able to complete all expected feature functionality within the Pieces for JetBrains Plugin. 
for a link to the Pieces for JetBrains Feature Checklist Please see the following [link](https://github.com/pieces-app/Pieces-Product-Checklists/issues/new?assignees=ben-at-pieces&labels=Chrome+Feat+CheckList%2C+JetBrains+Feat+CheckList&template=jetbrains-feature-checklist.md&title=%5B+Tester+%5D+JetBrains+Feature+Checklist+)




## Disconnect Tests
### With the extension installed and running, close Pieces OS and...

Upon Disconnecting from Pieces OS, users should expect the following notification for all of the cases below

![image](https://user-images.githubusercontent.com/101364072/232806033-336b147a-7112-455a-838e-40193e39b286.png)


**After Installation, the following action should NOT fail or present a redirect notification... In the cases below we will be purposefully disconnecting from Pieces OS.** 

## Close Pieces OS: 

**If on MacOS**, locate the Pieces OS Icon in the system trey (top bar) and quit the application. (selecting the x in the GUI only minimizes the window)

**If on Windows**, locate the Pieces OS Icon in the system trey (lower righthand side of the window) and quit the application. _(selecting the x in the GUI only minimizes the window)_

## Test Cases
here we will be testing feature functionality in the event that the user's Pieces OS is not actively running.

#### case 1: Saved Snippets
- [ ] saved snippets successfully refreshes after reconnecting to Pieces OS?  (should be automatic)
- [ ] Right Click Save to Pieces... successfully saved to Pieces after reconnecting to Pieces OS?
- [ ] Keyboard Shortcut Save to Pieces... Successfully saved to Pieces after reconnecting to Pieces OS

#### case 2: Explore with Pieces Insights...
- [ ] user was automatically reconnected to Pieces OS?
- _Pieces OS appears not to be needed for the "Explore with Piece's Insights" feature_
- _currently no refresh button within the Pieces Insights side bar menu. 

![image](https://user-images.githubusercontent.com/101364072/232831120-0bb5b5d2-9041-4ec5-83be-06934bb0865c.png)

![Screenshot 2023-04-18 at 12 01 30 PM](https://user-images.githubusercontent.com/101364072/232835870-4e9ea5eb-95d8-49eb-868a-28133d6e2e67.png)
#### case 3: Find Related Materials in Pieces
- [ ] right click "Find Related Materials" shows the following success notification & redirect
- [ ] user was automatically reconnected to Pieces OS and the window was popped to the users view

![image](https://user-images.githubusercontent.com/101364072/232829685-707cba3b-aa99-4e89-9593-329096c526d0.png)

- [ ] clicking "view" shows the related materials in the sidebar dropdown?
- [ ] the expanded side bar menu shows snippets related to the current selection?
- [ ] related materials refreshes after successfully reconnecting to Pieces OS?  (should be automatic)
![image](https://user-images.githubusercontent.com/101364072/232829931-27df93b5-9693-4421-bf98-18dba2d78a10.png)


#### case 4: Save to Pieces As...
- [ ] user was automatically reconnected to Pieces OS?
- [ ] expected...
![Screenshot 2023-04-18 at 11 42 00 AM](https://user-images.githubusercontent.com/101364072/232830386-2521f92e-5a2f-4b18-9e6b-ae2ee0d9dc48.png)



#### case 5:  Share via Pieces Link
- [ ] user was automatically reconnected to Pieces OS?
- [ ] snippet is saved to pieces prior to generating the shareable link? 
      - _**Clipboard** & **Save to Pieces** behavior can be modified in settings_
- [ ] successfully generate shareable link after reconnected to Pieces OS? (should be automatic)

![image](https://user-images.githubusercontent.com/101364072/232550761-ffe87bf5-4871-444f-bb19-ba7ad3daba3e.png)

#### case 6: My Saved Pieces
- [ ] user was automatically reconnected to Pieces OS?
- [ ] scrollable list view is displayed along side the "My Saved Pieces"

![Screenshot 2023-04-18 at 11 52 21 AM](https://user-images.githubusercontent.com/101364072/232833377-ad2f1864-c5bd-4dac-b1bb-9449d274c550.png)
#### case 7: Refresh Saved Pieces
- [ ] user was automatically reconnected to Pieces OS?
