# Nearsoft Apprentice - Git and Github.

**The purpose of this repository is to play with Git (commands and workflow) and contribute/share knowledge with others using Github.**

---- 
# Step 0:

Install Git on your computer.

# Step 1:

Sign Up for Github. The website will ask you for a username, email and password.

# Step 2:

Fork the repository [Apprentice-Git-Github](https://github.com/NearsoftApprentice/Apprentice-Git-Github). This will create a copy of the repository on your profile to start working with.

# Step 3: 
Open a Terminal and clone the repository you already forked (the one that is on your account), use the next command on your terminal (in case you're using a client, follow program wizard).

```bash
git clone https://github.com/NearsoftApprentice/Apprentice-Git-Github
```

This will create a copy on your computer of the repository.

# Step 4:

Check the status of the repository. It's a good practice to start doing this, ```bash git status``` will show you the current state of your repository.

```bash 
git status
```

# Step 5:

Create a directory with the initial of your first name and concatenate your last name. For example _Juan Resendiz_ will become _jresendiz_.

```bash
mkdir jresendiz
```

Now create a file called, _personal_information.txt_ inside the created directory and edit the file. You can add whatever you want on the file. Save the changes.

### Step 6:

Check the status of the repository. Git will show you that a new file exists and it's _Untracked_. The file will keep in that way unless we decide to add it. Let's add the file.

```bash 
git add jresendiz/personal_information.txt
```

### Step 7:

Check the status again, now you will see that the file that you created is part of the staging area and it's ready to be commited. Let's commit the file and add a message to that commit.

```bash
git commit -m "Creating my file"
```
> Don't forget to change the message and add something related to what you just did or write on the file.

