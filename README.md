# GA_GitHub_Tutorial

### Step 1
`Code This`

>Replace "Hello, World" with the message   
> ***I"m about to learn how to use Git and GitHub***

~~**`Console.WriteLine("Hello, World");`**~~

```csharp 
	public static void Main(string[] args) {
		Console.WriteLine("I'm about learn how to use Git and GitHub");
	}
``` 

*Save and run*

### Step 2

`Code This`

> Now add in separate `Console.WriteLines()` add the following messages. Make sure to add a new Line in between each to give them space. `\n`

> - Git is a Version Control System, it lets me save changes to my project in repositories.
> - GitHub works with Git to save those repositories online. Backing up my code and letting me work with others. 
> - I will start by ADDING GIT TO MY PROJECT

***Save and Run***

![Step 2 Run](Images/Step_2_Run.png)

`Do This`

Now on the top menu click **View** and Click `Git Changes`

![Step 2 Git Changes location in View Menu](Images/Step_2_GitChanges.png)

This will open a new window called `Git Changes`.

![Step 2 Git Changes Window](Images/Step_2_GitChangesWindow.png)

### Step 3

`Code This`

> In add the following messages to your code

> - **Adding Git To My Project
> - In order to add Git to my project, I have to add a .git folder to my project.
> - I can do this my clicking *Create Git Repository*
> - This will bring up a new window that lets me add Git to my project.


---

`Do This`
### Click "Create Git Repository"

![Step 3 Create Repo Window Edit](Images/Step_3_CreateRepoWindow_Edit.PNG)


Lets break down where we see here

**Initialize A Repository**

- Local Path : This is the location where your project is on your hard drive
- License Template : Don't worry about this now
- [x] Add README.md : This is a file that will allow you to display information. **Check This**

**Create a new GitHub Repository**
- Account : This is the name of your GitGub account, if this is your first time doing this on GitHub, you may have to log in.
- Owner: This should be your user name. It will auto fill when you log in.
- Repository Name: This will be the name of your project, online, on GitHub.
- [ ] Private Visibility ( **For Assignments: Make sure this is unchecked** ): This toggles if your Repository public or private. 
    - Checked: Your repository cannot be seen by anyone else.
	- Unchecked: Your repository is public and can be seen by others.

**Push you code to GitHub**
- A web url: This is the internet address for your GitHub repository. If you go to this location, you will see your repository. You can also find this by going to www.github.com. 

---

### For Your Projects

- **Check Add README.md**
- **Uncheck Private Repository**
- **Click Create and Push**


You've have now added Git to your project.

If it worked properly your ***Git Changes*** window will change. 

![Step 3 Git Commit](Images/Step_3_GitCommit.png)

---

### Step 4

You only have to **Add Git Once** to your project. Now we will learn the next 2 steps: ***`Commit`*** and ***`Push`***.

`Code This`

> Add these messages
>
> - I have added Git to my project.
> - I can now start committing my changes
> - Committing is how we tell Git to remember what changes I've made.
> - I can easily do this by Adding a Message and clicking commit in the Git Changes window

***Save and Run***

`Do This`

Now that we've changed our `Program.cs` file, lets look at our **Git Changes** window.

![Step 4 Changes Update](Images/Step_4_ChangesUpdate.png)

Since we've ***Updated and Saved our `Program.cs` file*** we can see our `Program.cs` file listed under ***Changes***. This mean we have updates we can ***`Commit`*** to our **Git**.

> ***What is committing?***

> Committing is when we tell Git to remember our new changes. Think of it like saving a current copy of the project. Except it's not saving the FULL project again. It is only keeping track of the changes between now and our last commit.

To ***`Commit`*** our changes to Git. You will enter in a message explaining the changes you made to your code in the Message TextBox. Following by clicking the ***`Commit All`*** button.

- In the MessageBox in our Git Changes window, type the message
    - **Add New Messages to Program.cs**
- Then click the ***`Commit All`*** button beneath the box.

![Step 4 Add Message](Images/Step_4_AddMessage.png)

`Program.cs` should now be gone from underneath ***Changes***.


---

### Step 5

Now we ***`Committed`*** our changes, we can ***`Push`*** those changes online.

`Do This`
![Step 5 Push](Images/Step_5_Push.png)

In the upper right corner of our **Git Changes Window**, you will find a Up arrow. This is the push button.

> What is ***`push`***?
>
> Push is the git term for uploading our current project repositories locally, online to GitHub

***Click The Push Button***

![Step 5 Push Successful](Images/Step_5_PushSuccessful.png)

If everyone goes smoothly you should have a message that say

> Successfully pushed to origin/main

> origin refers to GitHub, main refers to the branch were on. Those will be discussed at a later time.

To see everything come together click on the 3 dots to the right of the ***`Push`*** button. And click ***Open In Browser***.

![Step 5 Open In Browser](Images/Step_5_OpenInBrowser.gif)


This will open your web browser and bring your direction to your GitHub respository online. You should see all the files in your project. You can even click on files and see the code inside of them.

*This is the current project I have been building for this tutorial. Your projects will have different files depending on what's in it.*


![Step 5 Repo Online](Images/Step_5_RepoOnline.png)

---

### Repeat - Commit and Push

`Code This`

> Add these messages
>
> - My git workflow, once I have added Git to my project is
> - Save my project
> - Commit my changes
> - Push my Project

`Do This`

Now
- Save
- Commit
- And Push


### And that's it! You have added Git to your project, saved and committed your changes, and pushed your code online.

Why do this?

- Working with Version Control Systems ( Which is what Git is ), allows your code to easily be shared and backed up
- VCS are used everywhere in our industry. Git and GitHub are the largest, but there are others. What matters is you know at least on.
- GitHub is like cloud storage. It's where you save your project and backs while working.
- It is also our portfolio. When applying for jobs, Employeers will look at your github to see what projects you work on, the quality of your code, and what your interests are.
- We will also be submitting our assignments with GitHub.

Getting started with Git sooner than later will be a huge benefit to your career.