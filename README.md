# demo

Don't know how to create a GitHub account and Repository?
Let's learn together, step-by-step

1. Create a GitHub Account:
    a. Go to GitHub Website:
        Open your browser and go to https://github.com.
    b. Click on "Sign up":
        You’ll see a “Sign up” button in the top-right corner. Click on it.
    c. Enter your information:
        username, email address, password and click "Continue" or
        "Create account".
    d. Verify your account, complete puzzle or CAPTACHA
        GitHub may send a verification code to your email — 
        check your inbox and enter it.
    e. click "Continue".
    f. Your GitHub account is ready!
       Once you're in, you can start creating repositories, exploring code,
       and contributing to open-source projects.

2. Install Git on Your Computer:
    a. Go to https://git-scm.com/download/win
    b. Download the installer and run it.
    c. During installation, just keep clicking Next and accept 
       the defaults (they're beginner-friendly).
    d. When it's done, you’ll get a program called Git Bash — 
       like a command line.
    e. Open terminal and verify git is installed in your system and check
        its version by running below command

        git --version

3. Set Up Git with Your GitHub info:
    a. Open your terminal or Git Bash and type the following
        git config --global user.name "your github name"
        git config --global user.email "your@email.com"

    b. To check it's saved correctly:
        git config --list

4. Create your first GitHub repository:
    a. Go to https://github.com and log in.
    b. Click the + icon in the top-right corner → New repository.
    c. Fill in Repository name, description, Select Public 
       (for open sharing) or Private
    d. Check “Add a README file” (this gives your repo a starting file)
    e. Click Create Repository

5. Clone it to your computer:
    a. In your new GitHub repo page, click the green Code button and
       copy the HTTPS link. Then open your terminal and run:

       git clone https://github.com/your-username/my-first-project.git

       This will copy repo to your computer!

6. Make changes and push:
    a. Go into the project folder
        cd my-first-project
    b. Make a change, like editing the README.md. Then
       git add .
       git commit -m "My first commit!"
       git push origin main

       Your changes are now live on GitHub

Now you have GitHub account and git installed. You are there on your journey...

