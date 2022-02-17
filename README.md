Directions on how to use GitHub

Step 1: Signup for GitHub using this link https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home. GitHub will then lead you through the process of creating an account.
Step 2: Download GitBash using this link https://git-scm.com/downloads. Select the download of for your operating system and download GitBash.
Step 3: When GitBash is done downloading, find the download and install GitBash.
Step 4: Return to GitHub. You should be on your page. On the left side, locate the green button with the word 'New' next to an image of a book. Click on that.
Step 5: Name your repository, select if it is public or private, and click the checkbox next to 'Add a README file'. You can also click on the checkbox next to 'Add .gitignore', but it is not needed.
Step 6: Create a local repository by making an empty folder on your pc.
Step 7: Right click, and click on the 'Git Bash here' option. This will open up GitBash with the directory of that folder.
Step 8: With GitBash open, type 'git init'. This will initialize the local directory as a Git Repository
Step 9: Create a READEME.md file if you have not done so already, or have not selected the checkbox in step 5.
Step 10: Use command 'git add ." to add all files in your local repository to be commited and pushed to GitHub. Alternatively, you can use 'git add [name of file]' to add specific file
Step 11: Use command 'git commit -m "commit message" to commit the push. Make sure that the message is meaningful and descriptive
Step 12: Use command 'git branch -M main' to connect to your main branch.
Step 13: You will now need either the HTTPS or the SSH of your GitHub repository. You can find it on your repository by clicking the green button that says 'code'. Git hub might also give you the HTTPS or SSH on the repo, as well as a quick start guide.
Step 14: Using the HTTPS or SSH, use command 'git remote add origin [HTTPS or SSH]' to connect to your local and remote repositories.
Step 15: Use command 'git push -u origin main' to push local changes onto your remote repository.