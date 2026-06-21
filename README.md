# Cursor-IDE Setup
<details>
<summary> <b> 📑Table of Contents</b></summary>

* [Introduction](#introduction)
* [Tools Installed](#tools-installed)
* [Setup Steps](#setup-steps)
* [Issues Encountered](#issues-encountered)
* [Outcome](#outcome)
* [Useful Links](#useful-links)
  
</details>

## Introduction
This repository documents the installation and setup of Cursor IDE along with Claude Code & Codex extensions. 

## Tools Installed
1. Cursor IDE
2. Extensions installed 
   + Claude Code Extension
   + Codex Extension
3. Git
4. GitHub

## Setup Steps
1. Downloaded and installed Cursor IDE from
   > https://cursor.com/download
   - Download for Windows [select path/location where to download]
   - Installed Cursor IDE.
3. Opened Cursor IDE and sign up or log in.
   - Sign in using Google account, GitHub account or Apple account
   - click on 'Start Building'
   - New Project [select 'New project' location as per need]
5.Installed Extensions from the Extensions marketplace.
    - Open the Extensions panel
        +  **Method 1**
           ```sh
              Ctrl + Shift + X
           ```
       + **Method 2**
           1. Click View on the top menu bar.
           2. Select Extensions from the dropdown menu.
    - Installed the *Claude Code extension*
        1. Open the Extensions panel.
        2. Search for Claude Code.
        3. Click Install.
        4. Sign in to your Claude account if prompted.
    - Installed the *Codex extension*. *(Similar steps as above)* 
       
        1. Search for Codex in the Extensions panel.
        2. Click Install.
        3. Sign in to your OpenAI account if prompted.
           
  > [!NOTE]
  > Depending on the extension version and existing account sessions, you may not be prompted to sign in to OpenAI or Claude during installation. 

8. Created a public GitHub repository.
   - Log in to GitHub.
   - Click New Repository.
   - Enter a repository name.
   - Select Public visibility.
   - Create the repository.
9.  Created a README.md file documenting the setup process.
10. Committed the changes to Git.
11. Download Git for GitHub repository connection in Cursor IDE
    -    Click View on the top menu bar.
    -    Select Source control from the dropdown menu.
    -    click 'Download Git for windows'
      > https://git-scm.com/install/windows [used recommended setting]
    - After installation is completed reload Cursor IDE 
12. Connect GitHub to Cursor IDE.
     - open Cursor IDE 'Editor Window' [ctrl + shift + N]
        > Click File on the top menu bar.
        > Select 'New Editor Window' from the dropdown menu.
     - Select Source control from the dropdown menu. 
     - Click 'clone repository' from GitHub
     - Select 'clone from GitHub' [visible in command palette]
     - Sign in to GitHub account
     - Select the Repository
     - Set the Repository destination 
13. Open the Repository 
  
## Issues Encountered
1. No login prompt appeared for the Claude Code and Codex extensions.
   - **Solution:** Since I signed in to Cursor using my Google account, both extensions were automatically signed in.

2. GitHub connection option was not visible.
   - **Solution:** Reloaded Cursor IDE, after which the GitHub connection option became available.
     
## Outcome
  - Successfully installed Cursor IDE.
  - Successfully installed the Claude and Codex extensions in Cursor IDE.
  - Successfully created a public GitHub repository and connected it to Cursor IDE.
    
## Useful Links
  + https://cursor.com/download
  + https://git-scm.com/install/windows
  + https://GitHub.com/
