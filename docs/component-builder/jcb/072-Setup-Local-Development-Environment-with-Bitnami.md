# SETUP LOCAL DEVELOPMENT ENVIRONMENT WITH BITNAMI

### Bitnami - Distributor Of Images

[00:00:00](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h00m00s)
(Click on these time links to see Youtube video)

I want to give you a quick tutorial on how to use Bitnami on your local development environment. Bitnami is a very well known Distributor of images. They are in association with Amazon. For a local developing environment, I found it most convenient. But only if you are not afraid of command line which you should not be. Command-line is an amazing world for you to make use of as a developer. It will be good for you to just jump in. 

### Installing Bitnami Joomla Stack

[00:00:43](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h00m43s) 

The first thing, google Bitnami Joomla together and see there is a download Joomla Bitnami and Bitnami Joomla installer and how to install Bitnami Joomla. Even on Joomla, documentation installing, Joomla using Bitnami, Joomla. Open the link. [00:01:13](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h01m13s) It has a recommended stack for Windows, Linux, and Mac. You will get a little setup Bitnami Joomla Stack tutorial. It will take you through the process of installation, helps you select the place, adds information and then you are done. [00:01:42](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h01m42s) It does what other similar components do, but I have experience it is targeting Joomla, it does and places everything. You could click on the Bitnami website link or you can click there at the bottom where it says Bitnami.org stack Joomla. That is the same as the first one. You could also click on this result. I should download it and run it but because I am on a Linux environment you would click on WIN/MAC/LINUX. [00:02:26](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h02m26s) Select the environment which you are in. Click Download. I am waiting for the download to start. Save the file to your local system. Run the file. 

### Download - Using Windows/Mac/Linux

[00:02:54](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h02m54s)

If you are using Microsoft, they have executable (exe) file, you can double click on it and that should get you going. The same goes for Mac. You can double click on the file and it will run you through the tutorial. I am using Linux which is a little bit different because it using a run file and you need to start it from the command line. As you can see [00:03:35](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h03m35s) I have downloaded it, and it already has Joomla 3.8.11. It is always up-to-date. If you are on a Linux system you would open in the terminal, do a quick `ls la` and will see the file is not executable.  We will make it executable. They will be `sudo chomd +x` and the file name, enter. It will ask you for your password. Type in  `chmod`. [00:04:23](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m23s) The file is executable. Check it out its '`sl`' is correct. Once you have done that you can close the command line. It was to run this `chmod` command over here to make the file executable which is safe and making sure that it runs correctly. [00:04:53](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m53s) You could double click on the file in your file system. It should start a Bitnami tutorial. Select language, Welcome to Bitnami Joomla Stack, and 'yes' we want all of this installed. We are going to set /home/llewellyn/joomla_bitnami [00:05:36](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h05m36s) and click next. You can give some defaults. I'm going to add a simple password, click next. It's asking for MySQL Server port. I know that I've already had MySQL installed. 3 0 7 should be OK. Giving it a name. [00:06:10](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h06m10s) I'm not going to do email or try and link up with Bitnami's Cloud.  

### Run The Installer - PHP, MySQL, Joomla With Its Database 

[00:06:20](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h06m20s)

It's going to run the installer and deploy everything you need. The PHP, the MySQL, Joomla with its Database. It is setting everything up for you. If you are going to do local development, I suggest using this path because it takes care of everything for you. Do it in a way that it doesn't affect your already existing PHP, and SQL and everything else. It packs it into a folder which [00:06:58](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h06m58s) I'm using. It is doing the MySQL, Database, creating the databases. This can take longer depending on your system's resources. Removing the things that it doesn't need. It sets up an uninstaller script. If you didn't like this, you could then undo it. [00:07:46](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h07m46s) We are done. Now you can launch the Bitnami Joomla Stack. Click finish. There we go. We have it installed. 

### Access Joomla - Joomla Website - Administrator - Login
 
[00:08:10](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h08m10s)

To access the Joomla sign, I'm going to use my Local IP, and add Joomla and there is our Joomla website. To access the Administrator. To login they have default passwords and stuff set. The one that you typed in during the installation. We want to have JCB. We install the web tab and we type JCB and enter. It comes up, click on it and install. It will grab the master branch which is in sync with the latest release. [00:09:00](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h09m00s) Install. It's also not counting these downloads. That's one of the reasons, we don't have any idea how many are using JCB at the moment. 

### JCB Installed - Grab Packages - Importing Packages

[00:09:13](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h09m13s)

Once it's installed you can go and open JCB. We are now on a little screen issue, I'm downsizing a bit. Let's grab a demo package by going to install JCB packages. There is VDM Packages and JCB Community Packages. We can grab any of these. Take the Hello World and get the package. As you can see I have not done anything. I've deployed Bitnami, I haven't touched any other feature of PHP or anything else. It grabs the package and it validates the checksum for us, we force it to update. Click continue. [00:10:13](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h10m13s)  It's importing the Hello World component.  To quickly show it. Compile Hello World and install. Hello World is there and it is working. 

### Doing Everything That Is Expected

[00:10:40](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h10m40s)

We can add a greeting, and it is doing everything that is expected. We can also check the front-end, Main menu. Change the Main Menu by using the Hello World greetings. Save and close. Just before we do that, we can go back to Hello World, we open the options, check out the permissions. We search for Site. We will see there are two and they're already set to allowed 'Greetings'. If not you change them to allow for the public. [00:11:14](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h11m14s) That is the two areas you would like. You can click 'Sign'. There is some text you will see it. We have not given the public the edit rights. It will say that it's not available, but it can check some text and go back home. We will see that the Hello World tutorial is functioning on our Bitnami within 11 minutes. [00:11:46](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h11m46s) 

That was a quick demonstration of setting up a local developing environment with Bitnami. The reason why I take this path is primarily because of what I'll show you next. Here you have the Bitnami folder, remember we've typed it in. There's Apache.

 There are all the files. If you want to go into the apps folder then into the Joomla folder [00:12:17](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h12m17s) and into the 'htDocs' folder. Here is your whole Joomla website and you can open and go in and work on your components and edit its files. This is the biggest reason I want to be able to easily access the files and work with them. It is very doable here. 

### New Feature - phpMyAdmin 

[00:12:40](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h12m40s)

The other feature which just comes out of the box by default is; If you go back to Joomla Bitnami, You'll see in the apps folder, that it have the 'phpmyadmin' installed. You could type in the URL 'phpmyadmin' and be right there able to access 'phpMyAdmin' and check out its databases. This all Bitnami did out of the box without real complications. That's the reason I like using Bitnami on my local developing environment. They are quite quick with the updates. If you go back to that folder, you'll see that it has 'Uninstall' and a 'Manage files'. [00:13:39](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h13m39s) You could run this one to uninstall and you can run this one to manage the environment which checks whether the server is up, the configurations and Civil events and stuff like that. You can stop all. The other one which I like is that you can click Uninstall. Do you want to uninstall Bitnami Joomla stack and all its models, say 'Yes'. It starts to uninstall everything, removes everything. You could run this, do some work. Save your components, export your JCB packages and then complete this thing and [00:14:28](https://www.youtube.com/watch?v=zpS52k89YcI&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h14m28s) move on. But it's dangerous, do keep in mind it really removes everything. 