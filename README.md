# Github guide

<h2>How to get your workstation ready for your first github project.</h2>
<b>1. Create a github account (If you already have one you can skip to the next step).<br /></b>
Go to this link: https://github.com/join?source=header-home<br />
Fill in the details and choose your plan. After that you have to verify your entered email adres and voila, your github account is created and verified. <br> <br />
<img src="img/screen1.jpg" width="50%">
<br />
<b>2. Install git<br /></b>
Go to this link: https://git-scm.com/downloads and download the correct file for your workstation system.<br />
Open the file and install it <br> <br />
You can verify if the installation was successfull by opening up your command prompt and type "git".<br />
<img src="img/screen2.png" width="50%">
<br />
<b>3. Create a github folder</b><br />
Create a folder you would like to use for your github projects.
When your folder is created go to your command prompt and go to the folder location by using the command "cd" for example "cd C:\Users\Hilgon\Desktop\github" <br> <br />
After that you enter the command "git init" this makes the folder a github folder.<br />
<img src="img/screen3.jpg" width="50%">
<br />
<b>4. Find a project you like to use or create your own</b><br />
When you have found or created a github project, you click on the green button called "Clone or download" and you copy the provided link.<br />
You go back to your command prompt and go to your github folder location.<br />
Run this command "git clone copiedlink"<br />
This will copy the entire project to your github folder. <br> <br />
<img src="img/screen4.jpg"> <br>
Voila, now you have the entire project on your workstation.<br />
<br />

<b>If this doesn't work for you to find the command line you can also try this.</b><br />
Click on windows icon left in the corner you type in cmd, then click on cmd with your right mouse button than you click on start up as administrator than cmd will start up. Now we need to type in the commands to get the project php-inloggning link: <b>https://github.com/HighSounDD/php-inloggning</b> in your git map. Go to you cms and type in cd \ that means that you are going to chose where you want to place the file <b>"php-inloggning"</b>. now you type the folder name in for example this is the folder where you want to place the project in <b>"C:\Users\Hilgon\Desktop\github"</b> than you need to type in your cmd <b>"cd xampp\htdocs\GitHub"</b> you have know selected the map Github. after that you type the in <b>"git clone"</b> after that you type the name of the project we take the project <b>"php-inloggning"</b> what your going to do is go to the project and click on clone or download than you see the <b>link:https://github.com/HighSounDD/php-inloggning.git</b> type this link after git clone  like this <b>"git clone https://github.com/HighSounDD/php-inloggning.git"</b> if you enter you have create your own project. <br>

<img src="img/uitleg.png"> <br>

<h2> FAQ </h2>
<b>What do you do if a project gets updated?</b><br />
When a project gets updated you open up your command prompt and go to your github folder location by using the command "cd".<br />
Copy the project linke again and you run the command "git fetch copiedlink"<br />
Then the project will fetch the new updated files<br />
<br />
<b>How to fork a project</b><br />
Go to the project you want to fork and click on the fork icon (Right top of the screen). This copies the project to your own github account.<br />
Now you can clone this project to your workstation and make your own changes.<br />
<br />
<b>How to make a pull request to the master project</b><br />
You forked a project and you made some changes that you want the master project to have. You can make a pull request.<br />
The owner of the project decides if he implents the pull request.<br />
Go to your forked project and click on the button called "New pull request".
Click on the button called "New pull request" and click your forked project
<br />
