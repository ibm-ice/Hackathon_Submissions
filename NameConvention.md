# TechSprint Submissions

Welcome to the official repository for the TechSprint Hackathon submissions! This repository is where participating teams will submit their code, presentations, videos, and design documents. Please follow the guidelines and naming conventions below to ensure that your submissions are properly organized.

## Table of Contents
- [Naming Conventions](#naming-conventions)
  - [Branch Naming Conventions](#branch-naming-conventions)
  - [Folder Naming Conventions](#folder-naming-conventions)
  - [File Naming Conventions](#file-naming-conventions)
  - [Pull Request Naming Conventions](#pull-request-naming-conventions)
  - [Commit Message Naming Conventions](#commit-message-naming-conventions)
- [Submission Guidelines](#submission-guidelines)
  - [Folder Structure](#folder-structure)
  - [Submission Process](#submission-process)
- [Review and Feedback](#review-and-feedback)
- [Closing Submissions](#closing-submissions)

## Naming Conventions

### Branch Naming Conventions
- **Team Branches:** 
  - Format: `team-[teamname]-submission`
  - Example: `team-alpha-submission`, `team-bravo-submission`
  - Purpose: Identifies which branch belongs to which team easily.

### Folder Naming Conventions
- **Main Team Folder:**
  - Format: `Team_[TeamName]`
  - Example: `Team_Alpha`, `Team_Bravo`
  - Purpose: Organizes submissions by team in the repository.

- **Subfolders for Different Types of Files:**
  - **Code:** `Code/`
    - Example: `Team_Alpha/Code/`
  - **PPT (Presentation):** `PPT/`
    - Example: `Team_Alpha/PPT/`
  - **Video:** `Video/`
    - Example: `Team_Alpha/Video/`
  - **LLD (Low-Level Design Document):** `LLD/`
    - Example: `Team_Alpha/LLD/`

### File Naming Conventions
- **General Naming Conventions:**
  - Use `snake_case` or `PascalCase` for file names (choose one and apply consistently).
  - Include a brief description of the file content in the name.

- **Specific File Types:**
  - **Code Files:** 
    - Format: `main_code.py`, `team_alpha_app.js`
  - **PPT Files:** 
    - Format: `Team_[TeamName]_Presentation.pptx`
    - Example: `Team_Alpha_Presentation.pptx`
  - **Video Files:** 
    - Format: `Team_[TeamName]_Demo.mp4`
    - Example: `Team_Alpha_Demo.mp4`
  - **LLD Documents:** 
    - Format: `Team_[TeamName]_LLD.pdf`
    - Example: `Team_Alpha_LLD.pdf`

### Pull Request Naming Conventions
- **Pull Request Title:**
  - Format: `[TeamName] Final Submission`
  - Example: `[Team Alpha] Final Submission`
  - Purpose: Clearly identifies the team’s final submission.

- **Pull Request Description:**
  - Include a brief summary of the submission.
  - Mention key components (e.g., “This PR includes the final code, a working demo video, and the LLD document for Team Alpha.”).

### Commit Message Naming Conventions
- **Commit Messages:**
  - Format: `Team [TeamName]: [Action/Description]`
  - Example: `Team Alpha: Added final code`, `Team Bravo: Updated PPT`

## Submission Guidelines

### Folder Structure
Each team should organize their submissions in the following folder structure:

**Structure :**  /Team_[TeamName]/ /Code/ /PPT/ /Video/ /LLD/


1. /Team_Alpha/ /Code/ /PPT/ /Video/ /LLD/
   
```bash

### Submission Process
**Clone the Repository:**
git clone https://github.com/ibm-ice/TechSprint_Submissions.git
```
2. Create a New Branch:
Create your branch using the following command:
```bash
git checkout -b team-[teamname]-submission
```
  Replace [teamname] with your actual team name (e.g., team-alpha-submission).

3. Add Your Work:
  Place your code, presentations, videos, and LLD documents in the appropriate subfolders.

4. Commit and Push Changes:
```bash
git add .
git commit -m "Team [TeamName]: [Description of changes]"
git push origin team-[teamname]-submission
```
5. Create a Pull Request:

  After pushing your branch, create a pull request with the title [TeamName] Final Submission to submit your work for review.
