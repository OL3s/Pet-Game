# Virtual Pet Game

## How to Copy and Update the Project
### Contents
- [Make Git Work Properly](#to-make-git-work-properly-you-need-to-have-git-installed-on-your-computer)
- [Copy the Project](#to-make-a-copy-of-this-project-on-your-computer)
- [Save and Update Changes](#to-save-your-changes-and-send-them-to-the-online-project)

### **To make Git work properly, you need to have Git installed on your computer.**
1. **Download and install Git** from [git-scm.com](https://git-scm.com/downloads).
2. Press the **Button** stating **Download for Windows** (or your operating system) to download the installer.

    ![Download](/Git-Manual/image-1.png)

3. Press the **Standard Installation** called "Git for Windows/x64 Setup." 

    ![Install](/Git-Manual/image-2.png)

### **To make a copy of this project on your computer:**
1. **Right-click** inside the folder where you want to put the project.
2. Click **Open in Terminal** (see picture below):

   ![Open in Terminal](/Git-Manual/image.png)

3. In the terminal window that opens, type:
   ```bash
   git clone https://github.com/OL3s/Pet-Game.git
   ```

---

### **To save your changes and send them to the online project:**
1. Open the terminal inside your project folder  
   (Right-click the folder and select **Open in Terminal**—see the picture above).
2. Type these commands, one at a time:
   ```bash
   git pull
   git add -A
   git commit -m "Write what you changed here"
   git push
   ```
3. Git will automatically detect all changes, including images and other files, and only update the files (including images) that have been changed. This means you don’t have to worry. Your work will always be safe, up to date, and nothing extra will be overwritten.

## Game Details

**Title**: Virtual Pet Game
**Version**: 0.0
**Operating System Target**: Android  
**Resolution**: 540 x 960 (Portrait)  
**Engine**: GameMaker Studio
**Language**: GML (GameMaker Language)
**License**: Proprietary  
**Author**: OL3s (Ole-Kristian Wigum) & H...
**License URL**: *(Not open source. All rights reserved.)*

## Overview
A virtual pet mobile game where players care for a pet by feeding, playing, and resting it.

## Features
- Touch-based controls
- Mobile-friendly layout