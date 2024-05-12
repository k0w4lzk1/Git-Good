Step 1: Install Git For Linux: -> sudo apt install git-all

For Mac and Windows:

Download and install Git from the official website:

Git for Mac
Git for Windows

Step 2: Create a GitHub Account

-> Visit GitHub and sign up for an account.

Step 3: Install GitHub CLI (Optional)

For Linux:

-> sudo apt install gh

For Mac (using Homebrew):

brew install gh

Step 4: Set up GitHub CLI

Run the following command to set up your GitHub CLI account:

bash

gh auth login

Follow the prompts:

What account do you want to log into? - GitHub.com (use your up and down keys and press enter)
What is your preferred protocol for Git operations? - HTTPS
Authenticate Git with your GitHub credentials? - Yes
How would you like to authenticate GitHub CLI? - Login with a web browser

Lastly If an error does occur while commiting its most likely something to do with your username and password

git config --global user.name "<name in github>"
git config --global user.email "<email in github>"

Resources https://www.simplilearn.com/tutorials/git-tutorial/git-installation-on-windows

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

https://cli.github.com/manual/

this should be on a new branch

What has changed

another thing not in the main
