# Module 3 Journal: Remote Git & GitHub

**Date:** Feb 2, 2026
**Topic:** Remote Repositories and GitHub

## Key Concepts & Learnings

### The Difference between Git and GitHub
The biggest takeaway from this module was solidifying the distinction between the two tools. Git is the local version control system installed on my machine and GitHub is the remote service that acts as a central hub. Even though Git is distributed—meaning everyone has a full copy of the history locally—we use a remote server like GitHub to facilitate teamwork so we don't have to be online simultaneously to share code.

### GitHub is more than storage
GitHub isn't just a backup drive. It is a full development platform.
* **Forking:** This allows me to copy a project to work on it independently. This is the backbone of Open Source contribution.
* **Pull Requests (PR):** This is the workflow for submitting my changes back to the original project.
* **Documentation:** The `README.md` file is critical because it acts as the front page of the project since it explains what the project does and how to install it.

### Connecting Local to Remote
Chapter 9 cleared up the syntax for linking my computer to GitHub. The command `git remote add origin [link]` is the bridge between my local folder and the cloud. I also learned that "origin" is simply the standard naming convention for the primary remote repository, not a hard-coded requirement.

## Difficulties & Troubleshooting

* **Authentication:** The text noted that authentication issues are common when pushing code. And it's often due to password managers or incorrect credentials. I need to ensure my global config is set correctly using `git config --global` to avoid permission errors.
* **SSH vs. HTTPS:** I initially found the difference between connecting via SSH and HTTPS confusing. However, I now understand that setting up SSH keys allows for secure access without needing to type a username and password for every single operation.

## Future Reference / Cheat Sheet

I want to retain these commands for future assignments:

* **Check Remote Link:**
    ```bash
    git remote -v
    ```
    *Use this to verify which server I am currently linked to.*

* **Pushing Code:**
    ```bash
    git push -u origin master
    ```
    *Use this to upload local commits to the remote branch.*

* **Hosting:**
    * Remember **GitHub Pages** for hosting simple websites directly from the repository.
