---
name: Pieces Suite Installer (Only Windows)
about: This checklist walks the tester through the installation process associated
  with the Suite Installer. (Installs both Pieces OS and Pieces for Developers))
title: "[ Tester ] Pieces Suite Testing Checklist"
labels: ''
assignees: ben-at-pieces

---

# Feature Checklist: Microsoft Windows MSIX Installer (Pieces Suite Installer)

## Getting Started with the Pieces Suite Installer

- [ ] If you’ve previously installed Pieces from the Microsoft store, you must uninstall older versions of Pieces for x and Pieces OS to leverage the Pieces Suite Installer. 

    💡 **Steps to Uninstall Pieces Desktop Apps**
      _POS & PFX_
    1. Start Menu > All Apps
    2. Right-click on Pieces OS and click “Uninstall”
    3. Right-click on Pieces for Developers and click “Uninstall”
    
    
![image](https://user-images.githubusercontent.com/101364072/233148990-2b9290af-04b8-4183-9e67-0607b74a349f.png)


- [ ] **FAQs:**

    - [ ] **Why do I have to remove older versions of Pieces OS and Pieces for Developers?**

      - The Pieces Suite Installer inspects your device for updates (if using production just check for the update)
      - **BUT...**
      -  if previous versions were installed from the Microsoft store or the Pieces Builds Client you will need to Uninstall to ensure consistency within the test environment.

## Steps to Install:

- [ ] Navigate to the [Pieces Install Page](https://code.pieces.app/install)
- [ ] Select “**Install**”

    ![image](https://user-images.githubusercontent.com/101364072/232084471-089a186c-cdab-444a-931b-d71c66603af0.png)

- [ ] You will be redirected to a pop-out app installer page. You can find this in the system tray in the lower right side of your screen.

![image](https://user-images.githubusercontent.com/101364072/233147834-0afe207f-e4aa-43ea-9779-7f858f511a41.png)

![image](https://user-images.githubusercontent.com/101364072/232086694-2142db23-e7a6-4a36-94bd-76bd77a1f222.png)

**Note:** users will need to allow the installer/POS/PFX to access diagnotic information.
    _by opting out, the users diagnostic information will not be tracked...._

- [ ] After making this selection, users will see the Pieces Suite Installer beginning to install Pieces OS and the Pieces Desktop App.

    ![image](https://user-images.githubusercontent.com/101364072/232075445-b5da18b3-34e0-4432-8012-2b5a3d8913c8.png)

- [ ] You should be brought back to Pieces website and see a screen that says “Thanks for downloading Pieces!” You should also see the Pieces for Developers application launch on screen.

- [ ] You’ve now successfully launched Pieces OS and Pieces for Developers!

## Checking for Updates

**the all-in-one package application that downloads and installs Pieces OS and Pieces for Developers in a single click!**

- [ ] be sure you're fully up to date...  open the Pieces Suite Installer and select "Check for Updates"

   _this is applicable for both Pieces OS & the Pieces Desktop App.
![image](https://user-images.githubusercontent.com/101364072/233150566-8767e7cd-6971-4048-b6a9-bf6d65ae7727.png)

## About
- [ ] user is redirected to the proper About Pieces [link](https://pieces.app/about/)

## Get Help 
- [ ] user is redirected to the proper support redirect [link](https://docs.pieces.app/)

## Submit Feedback
- [ ] is the typeform redirect proper.
