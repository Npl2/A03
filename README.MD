
Random Note ~ to break up a line in a ".md" file, double space at the end of the sentence.  

Installation Process
-
###Webstorm:  
1 - Download the latest version of WebStorm from JetBrains, https://www.jetbrains.com/webstorm/download/#section=windows.  

2 - Go to the location you placed the download and install it. It will ask you if it can make changes to your device, click yes.  

3 - It will prompt you with a welcome page. Next it will ask you for a install location. You can use the default location or change it.  

4 - Next it will ask you how you want to configure WebStorm. You can choose any that fills your requirements.  

5 - Next it will ask you to choose a start menu folder, you can leave it as default. Now click install.

###Git:  

1 - Download the latest version of Webstorm from git, https://git-scm.com/downloads.  

2 - Choose the operating system you plan on using. Then click, "Click here to download" for the latest version.  

3 - Go to the location you placed the download and install it. It will ask you if it can make changes to your device, click yes.  

4 - It will prompt you with its license. You can read it and click next.  

5 - Next it will ask you how you for a install location. You can use the defualt location or change it.  

6 - For the next 14 pages, I left them as default. You can change them to fit your needs.
****
Creating a Repository and Connecting it to GitHub:    
-
1 - Open Webstorm and press (Ctrl+Alt+S)  

2 - Left Bar Menu: Choose Version Control -> Git  

3 - Click the "Test" box.The default location box should be C:\Program Files\Git\cmd\git.exe otherwise it is C:\Program Files\Git\bin\git.exe.    

If you installed Git correctly it, the version of Git should appear below the path bar. If not follow the instruction for Git in the Installation process above.  

4 - Now click "Create New Project" on the main page  

5 - Choose a location and give the project a name. I chose IS117DemoS20.  

6 - Click "Create".  

7 - Top Bar: Click File -> New -> HTML File -> HTML 5  

8 - Change the content of the file to anything you want I choose to add a heading and a sentence.  

9 - Top Bar: Click VCS -> Import into Version Control -> Create Git Repository 

10 - Now commit changes to GIT. Choose your file and right click and choose "Commit File"  

A dialog box opened and type what you added/changed in the file.  

Click Commit.  

11 - Now add the project to GITHUB. 

TopBar: Click Git -> GitHub -> Share Project on GitHub

Change shareby to your account. If you did not sign in, there is link to sign in. Click that and it will ask you for permission to connect your Jetbrains account to Github. Click "Allow".

Once you connected your account go back to Webstorm and click "Share".

This message should appear, "Successfully shared project on Github".

12 - Go to your GitHub account on the browser and go to your repository.

13 - Now create a README.MD file.

Click Add file -> Create new file

Name it README.MD and add content to it.

14 - Now go back to Webstorm and make a change to your file

15 - Once you made a change right-click on the file and choose "Commit"

16 - Type "2nd version" in your dialog box and click "Commit and Push"

17 - Choose your commit message, in this case it is "2nd version" and press "Push".

18 - Now the change should be added when you visit your repository.
****
Glossary:
-
**Branch** - is a instruction that tells a computer to begin executing different instructions rather than simply executing the instructions in order.  

**Clone** - the process of creating an exact copy of another application program or object

**Commit** - updating of a record in a database.  

**Fetch** - is the retrieval of data by a software program, script, or hardware device.   

**GIT** - a software for tracking changes in any set of files, version control system  

**Github** - a web-based version-control and collaboration platform for software developers

**Merge** - is the process of combing the carious versions of a file or folder  

**Merge Conflict** - an event that occurs when Git is unable to automatically resolve differences in code between two commits  

**Push** - a command to used to upload local repository content to a remote repository 

**Pull** - used to fetch and download content from a remote repository and immediately update the local repository to match that content   

**Remote** - a git command that is one piece of the broader system which is responsible for syncing changes  

**Repository** - a central file storage file location 
****
References:  
-
Techopedia. “What Is a Branch? - Definition from Techopedia.” Techopedia.com, Techopedia, 21 Sept. 2016, https://www.techopedia.com/definition/18058/branch. 

Techopedia. “What Is Cloning? - Definition from Techopedia.” Techopedia.com, Techopedia, 20 June 2016, https://www.techopedia.com/definition/31923/cloning-programming. 

Techopedia. “What Is a Database Commit? - Definition from Techopedia.” Techopedia.com, Techopedia, 29 Aug. 2011, https://www.techopedia.com/definition/16/commit#:~:text=In%20a%20general%20sense%2C%20a,users%20to%20see%20the%20changes. 

Techopedia. “What Is Merge? - Definition from Techopedia.” Techopedia.com, Techopedia, 15 Sept. 2015, https://www.techopedia.com/definition/1217/merge#:~:text=Merge%20is%20the%20process%20of,of%20data%20in%20a%20file. 

“What Is Fetch?” What Is Fetch?, Computer Hope, 16 Aug. 2021, https://www.computerhope.com/jargon/f/fetch.htm#:~:text=Fetch%20is%20the%20retrieval%20of,or%20displayed%20on%20a%20screen. 

Jenny Bryan, the STAT 545 TAs. “Happy Git and Github for the User.” Chapter 1 Why Git? Why GitHub?, https://happygitwithr.com/big-picture.html. 

Courtemanche, Meredith. “What Is Github? - Definition from Whatis.com.” SearchITOperations, TechTarget, 6 June 2018, https://searchitoperations.techtarget.com/definition/GitHub#:~:text=GitHub%20is%20a%20web%2Dbased,collaboration%20platform%20for%20software%20developers.&amp;text=GitHub%20facilitates%20social%20coding%20by,networking%20site%20for%20software%20developers. 

“How to Resolve Merge Conflicts in Git: Advanced Git Tutorial.” GitKraken, 7 July 2021, https://www.gitkraken.com/learn/git/tutorials/how-to-resolve-merge-conflict-in-git. 

Atlassian. “Git Push: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing/git-push#:~:text=The%20git%20push%20command%20is,exports%20commits%20to%20remote%20branches. 

Atlassian. “Git Pull: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing/git-pull. 

Atlassian. “Git Remote: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing. 

Atlassian. “Git Fetch: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing/git-fetch. 

“Repository.” Repository Definition, https://techterms.com/definition/repository. 

Hendela, Art. “ExtraInstallationInstructions.” Canvas, Professor Art Hendela, 15 Feb. 2020, https://njit.instructure.com/courses/21544/files/3171160?module_item_id=687830. 

