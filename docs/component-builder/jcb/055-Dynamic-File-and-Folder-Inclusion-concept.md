<div style="text-align: justify">

# DYNAMIC FILE AND FOLDER INCLUSION CONCEPT

### Introducing To A Feature - Adding Files, Folders As Code Or File To Your System

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

I would like to introduce you to a feature that we have been working on for quite some time now.  Most of the features already existed for quite a while. It is just that I have been trying to make it stable so that it will work well. [00:00:32](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h00m32s) In doing so I had to extend it a bit. This feature has two or three concepts that I would like to explain. [00:00:49](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h00m49s) It is about adding dynamic files, folders or even external files which might be on a website or on GitHub, and you want the content from that file and add it as code or even as a file to your system.[00:01:17](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h01m17s)  

I am working with components that are pulling data from all over the place. Most of these features are really what I needed to get projects going.  There is a feature that can be used to add files and folders. This feature has always been there. [00:02:03](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h02m03s) But currently I have expanded this by adding an 'Advance' tab to this feature. It got this Basic tab which is the normal one. I did explain in previous tutorials, how to get these files.  

### New Area - Advance

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=144" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

There is now a new area called 'Advance'. [00:02:35](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h02m35s) The 'Advance' area is able to grab files from anywhere in your system an add it to the component. It can be files outside of the root directory of your Joomla website.

### Note - Adding Files

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=173" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Just make sure that the PHP has the right to the file and can read it(See Video). But for most cases, it is not necessary to grab files outside the Joomla root directory, because we are just editing a custom file inside of our Joomla Component which we have created. [00:03:24](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h03m24s) But this file or these folders are not generated by JCB. We want those files where they are actively running inside of our component. We want them to be taken and put into the package without us having to move it around.  So you can like, I am doing here(see video).  [00:03:52](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h03m52s) There is a note; '_Please note... use constant paths_'. That you can use constant paths and the full path directly without quotes. That means you do not need to do like in PHP,(follow on video) you put this part in quotes. Well, you do not need to do any of that. You can put the constant directly like that and the compiler will deal with this and make it right. [00:04:21](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m21s)  You can do that also with folders as well as with files.

### Need To Set The Target Path And Relation To The Zip Package

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=269" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Then you need to still set the target path and relation to the ZIP package. You will have folders called 'Admin'. But here I am doing a folder called 'libraries/vdm_io'. [00:04:45](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m45s) That means I am targeting a folder which is not part of a component package but because I want that folder to be installed with my component every time, I do not want to have a separate package for this library. [00:05:15](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h05m15s) JCB has been improved to include this package, which is if you look at this(see video) will see that it is a composer file and I am including some Composer Classes there, which is now used in JCB. With each install, it is moved into its place. [00:05:39](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h05m39s)  That might be outside of the convention, but there are neither rules against it.

### JCB Detects You Are Not Targeting Normal Folders - Add A Little Script To Script Install

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=353" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

When JCB detects that you are not targeting the normal Admin, Media or Site Folders, which is not part of the expected component package folders, it will add a short script to the script install.[00:06:28](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h06m28s)  So that it move this folder into its correct place upon installation of the component or whether the component is updated.  I have the script file for Component Builder open and are going to scroll down. [00:06:58](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h06m58s) This new short script is way at the bottom, (`setDynamicF0ld3rs`) it does not conflict with any other method at any time. It gets the details from the above methods. Then it checks whether the folders get the dynamic install folder. It checks whether there is more than one.  [00:07:29](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h07m29s) Then if it is one of these Media, Admin, or Site, it ignores it, because those already being dealt with by Joomla. If it is not, it moves it into its correct place. This is a dangerous feature,  you must use this with caution because you can literally grab with this new function, anything anywhere from your Joomla website and overwrite it anywhere on the users installation website, which could be problematic.[00:07:59](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h07m59s)  Something you should not do unless it is your right to do so.  

This is the new feature in dynamic movement of folders and files.[00:08:25](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h08m25s) What makes this all so nice is if you are using these constants in the naming of the paths, if you export a JCB package and you import it at another JCB install, it remaps these files. It export them, remaps them and moves them back into place on the other install. That really makes it very convenient when working in a team where you want to have these files always to be the same everywhere.


### Heads Up - Consider With Whom You Are Sharing Packages - Part Of Security

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=553" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**NB. If you import a package from anyone they could move files through this method into your system,  and for security reasons you need to consider with whom you are sharing packages**. This is just a heads up regarding the new folder and file implementation.

### Use EXTERNAL CODE Snippet

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=589" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The other aspect which I mentioned earlier, where you are able to get content from anywhere works as follows. So anywhere in any custom area of JCB, where you can add a custom script, you can also use this 'EXTERNALCODE' Snippet. Now, this could be a URL or it could be a folder in your system. This folder does not yet work with Constants. It needs to be exact for the path at this stage but the reality is that with this EXTERNALCODE concept, you can take for example the variable from a Gits snippet. [00:10:36](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h10m36s)  
Let me illustrate. Here is what I have called 'fancydate' which is a few static functions that are not wrapped in the class yet. It is outside a class because I want to include it in my helper class with the snippet, that I can have others work with me on this code on GitHub. [00:11:07](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h11m07s)  If any changes are made to this code, it automatically updates my system. Now there might be some security concern in doing it. But a few tricks have been added in the compiler to notify you if there has been a change to the code. [00:11:36](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h11m36s)
It means that the first time you use that snippet to include this snippet that you have got here, use the 'Raw' function. Here is a text file. Grab that URL(see video) an add it. [00:12:11](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h12m11s)  Currently it is bound to a specific version which if anybody makes a change to the snippet, you will not get the new version. Well, that is the way to lock it in. But if you want it to be dynamic, you can remove a part of this(see video) and then you can use it like that.

### Specific Piece Of Text Dynamically Added To The Back End Of Component Builder

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=758" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Now this specific piece of text that you see here, will dynamically be added to my component. Let me demonstrate. I have opened Component Builder in its back end gone to this Libs & Helpers tab and scroll down to this area which is called Admin class. I will do it in the admin area so that it is easily detectable. [00:13:07](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h13m07s) I am going to add that snippet like that so it says EXTERNALCODE with the path of the URL. Save and close.

### When Compiled - It Should Tell You Have Added The EXTERNALCODE To Your Component

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=799" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Go to the Compiler. The moment it is compiled, it should indicate that this kind of external code has been added to your component. If not, something is wrong. It is supposed to tell you the first time you have added the snippet because it creates a hash of that snippet. [00:13:43](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h13m43s)  In the future if it changes, you get notified. When we grab the snippet from Github and anybody in the middle tampers with it, it will notify you that the snippet was changed. If you know that it should have changed because you made a change to the Gits snippet or someone else in your team did, [00:14:15](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h14m15s) then obviously you can be expecting that. You could still for safety sake go check in the code of the component where the snippet is being added to ensure that it is still accurate. Let's compile this.

### When Compile Two Messages Are Relevant To The Issue

* First Message

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=874" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

So we see two messages that are relevant to the issue at hand. The one deals with this folder which when it is placed in the Library folders and every time you would compile, it will notify you that it has been done. It will tell you that it has detected it and it has added the script to the script PHP. [00:15:11](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h15m11s) This first line here(see video), is showing you the snippet, and it is telling you there it has been added for the first time, and that you should examine it to ensure the correct code string was used. You should go to the place where the compiled package, where this (follow on video) should have been added, go and check that it is correct, that what you see here on GitHub, the string here, [00:15:44](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h15m44s) is also what you going to see in the code.

* Second Message

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=951" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Every time thereafter it should give you this little message here. It should tell you how many code strings are being added to this component as an external code, and to avoid shipping your component with a malicious code string, always make sure that the correct code string values are used. If we detect a change, it will also notify you.

### Do As Note Says: Check If It Is The Correct Code

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=976" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Let's go and check that it is the correct code. In the ZIP package, we see that this `library` folder has been added. Go to the `admin area`, `helpers`, open Component Builders `helper` file where I added the snippet. Let's just open that, `fancydate`, and `fancydatetime`. [00:16:53](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h16m53s) This whole selected area(see video) was taken from GitHub and put in the component. I am going to make a change to this snippet on GitHub. I'm going to just do something small so that we can see what happens if a change is made to this code, and how JCB responds. I am just adding this [00:17:20](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h17m20s) new short string saying (change was made) and click on this 'Updates Public Gist'. So it now tells us that it has been revised for a second time, and a change was made. Now let's compile the component without doing anything else, just make the changes here on GitHub, and go back to the component and compile it. We are selecting this and Compile. [00:17:51](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h17m51s) Some spacing between the messages should be added. It does not always seem clear enough that the messages are not related to each other like here it is showing that other message again. You might miss that. I need to give attention to this.

### Warnings Area

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_c7wzW075lA?start=1092" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Here in the 'Warnings' area, we see that it has 'changed' since the last compilation. Please examine that to ensure that change is safe. That means JCB has automatically detected that the snippet that you originally added has actually been updated. At this point, we anticipated that so. If we go and look at the code, we see that it just added this 'change was made'. [00:18:49](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h18m49s) The rest of it is exactly the way we want it. Everything is fine, it is a change we anticipated.

Nobody else has tampered with the script. Neither was there a man in the middle attack. In any case, if there is someone tampering with the script, it will end up as a string. If for instance something is put in here it will show this error in your file. [00:19:16](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h19m16s)  JCB will detect that and will see that the hash for the script is changed, and it will notify you with that message. Sometimes we want to include an external value in our component which is dynamically changing and want to do it without really thinking about it all the time. This is what this feature is ideal for. Use it with caution and know what you are doing or do not use it at all.
[00:20:15](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h20m15s)
That was a quick overview of the new folder file inclusion, as well as the external code inclusion features which I really trust would be useful to you. It is a powerful tool. I realize there is the danger of it being abused but at the same time I think component development works upon reputation and if you want to have a good [00:20:54](https://www.youtube.com/watch?v=_c7wzW075lA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h20m54s) reputation in the community, you should not do anything that will hurt others or damage their contribution, and their applications but you should steer within the parameters of your own component, and your own implementation.

</div>
