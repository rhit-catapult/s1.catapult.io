---
layout: page
title: Github Classroom Setup
---

# Github Classroom

Github classroom is a nifty framework that allows us to distribute and manage
the code that we will be building throughout this project. I have set up a
starter code for you that you will need to accept, and then you can add your own
code to the same project. Get excited, the fun parts of our project are about to
get started!

## Step 1: Create a Github account

If you do not already have one, please go ahead and create an account on
[github](https://github.com/). Choose a fun username, most likely that username will
stick with you throughout college!

## Step 2: Accept the Github classroom invite

<!--
TODO: Add here screenshots screenshots
-->

Next, click on the following [link](https://classroom.github.com/a/kH_CSyDC) and
accept the invitation to join our classroom. This will first invite you to join
our organization `rhit-CSSE`.

Next, you will see a screen like the one below. Click on the `Accept this
assignment` button:

![GithubClassroom 1]({{ site.baseurl }}/assets/img/GithubClassroom/00.png)

Next, you will see a screen that informs you that Github is configuring your
repository, as shown below

![GithubClassroom 2]({{ site.baseurl }}/assets/img/GithubClassroom/01.png)

Wait a few seconds, then hit the refresh button in your browser, you should see
the following message pop up

![GithubClassroom 3]({{ site.baseurl }}/assets/img/GithubClassroom/02.png)

Finally, click on the link that is shown in the page above, this will take you
to your repository where you can see the starter code, as shown below

![GithubClassroom 4]({{ site.baseurl }}/assets/img/GithubClassroom/03.png)

You are now good to go, we're so close to getting our hands dirty with coding.

## Step 3: Let's open up the project

Now it's time to get our hands dirty and start coding. But first, we must import
the project into PyCharm (I promise, this is the last step).

1. Launch PyCharm and click on the `Get from VCS` button, a screen should pop up
   like the one below

   ![Setup 1]({{ site.baseurl }}/assets/img/ProjectSetup/00.png)

2. Next go back to your favorite browser, and open the tab that has your
   repository on it. Click on the `Code` button, select `HTTPS`, and copy the
   link that shows up then.

   ![Setup 2]({{ site.baseurl }}/assets/img/ProjectSetup/01.png)

3. Paste the URL that you copied into the URL field in the PyCharm window. Your
   window should look like the following (your link will be different though)

   ![Setup 3]({{ site.baseurl }}/assets/img/ProjectSetup/02.png)

4. Click on the `clone` button. PyCharm might ask you for your GitHub username
   and password, so enter those as well. If everything goes well, you should see
   the project open up in your window looking like the picture below

   ![Setup 4]({{ site.baseurl }}/assets/img/ProjectSetup/03.png)

5. Now, let's configure python for our project. First click on the project
   properties (right click + properties on Windows, PyCharm -> preferences on
   MacOS) and expand the `project:PyGame...` tab on the left hand side menu.
   Select the `Python Interpreter` item from that drop down list. Your window
   should look as follows:

   ![Setup 5]({{ site.baseurl }}/assets/img/ProjectSetup/04.png)

6. In the `Python Interpreter` textbox on the right-hand side, make sure that it
   shows the version of python that you installed. PyCharm should automatically
   detect that for you. If it doesn't, then please contact your instructor or
   teaching assistant. 

7. Let's install PyGame now. Click the small `+` button underneath the `Python
   Interpreter` textbox, and type `pygame` in the search bar. You should see
   something that looks like this

   ![Setup 6]({{ site.baseurl }}/assets/img/ProjectSetup/05.png)

8. Select pygame and click on `Install Package`

9. Close the window, `pygame` should now appear in your installed packages menu
   as follows:

   ![Setup 7]({{ site.baseurl }}/assets/img/ProjectSetup/06.png)

10. Congratulations on making it this far. I know it's been tedious, but we are
    now good to go. 

