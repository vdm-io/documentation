<div style="text-align: justify">

# MAJOR RELEASE OF JCB v2.6.0

### Removing All Repeatable Fields in Joomla Component Area

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

I would like to demonstrate how to upgrade to JCB version 2.6.0. It is quite a major upgrade since we have removed all Repeatable Fields in the Joomla Component area. Joomla Component area has quite a lot of Repeatable Fields. On opening the component it may be seen that Repeatable Fields are little models that pop-up with values which had been used quite excessively in this view.[00:00:43](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h00m43s) The reason why this was done is because it is a very smart Field since it combines these values into one value. The JavaScript on the page grabs these values and converts it into one value, when on submission the form only submits one string, and not several Fields.[00:01:13](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h01m13s) There are some conventional reasons which make the Repeatable Fields on a SubForm level more desirable, due to its ability to validate the data more correctly. [00:01:34](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h01m34s) We had to remove these Fields because in Joomla 4 they no longer are supported. I had to decouple a number of these Fields into their own Tables because of the size of the values that are on the page, the page becomes immensely heavy. There had been about 9 new Tables added to JCB, to accommodate this.

### Changes Only Affects The Component Area

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=123" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The real change is only going to affect the Components Area. But because JCB is a very Dynamic Component that integrates with various levels of this Data Structures.  

### Upgrade: Compiler Import/Export Of JCB Packages

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=140" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Compiler had to be upgraded, as well as the import and export of JCB packages. We have tested this and for the most part, those involved with the testing, have found that this transition is a Major improvement to JCB and will be very easy and without any issues.

### Suggestion - Clean your Browser Cache and Browser Memory

 <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=167" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you run into glitches that do not work as expected, it is suggested that you clean your browser's cache as well as memory. It has been found that traces of the old Repeatable Field Structure and JavaScript surrounding that might clash with the new changes in JavaScript within the new update. To clear the browser memory and not just the cache, is quite important. Only after you have upgraded and started to work in different views, it will be seen that everything works as expected.

### Dynamic Get Area Some Conflicts

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=209" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Dynamic Get Area has been reported to have some conflicts at this stage. The Dynamic Get Area returns values from the Admin Area where, if we target let's say Back end View, and we grab some information. [00:03:55](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h03m55s) These values are returned from the Admin Area where it goes to this Admin View, and builds this structure. [00:04:04](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m04s) With this demonstration everything is working as expected. If this area is tested before the upgrade, it should work without any problems. If it does not, it is suggested to clear the browser memory and to try again until it is working like mine.[00:04:35](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m35s)  All that has been done was that I cleared my browser memory by going to history and wiped everything from this domain, so that there are no traces of JavaScript. If you do not want to clear all of the history then it specifically targets this domain that you are loading the JCB Component in.  

### Update in Managing Area

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=313" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The upgrade should be quite simple. Go to updates in the managing area. See that the upgrade is there and ready. Click on it and click update. Then the upgrade will be done. [00:05:41](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h05m41s) If you return to Joomla Component Builder, it should be 'up-to-date' and everything been done without any errors. In the Joomla Components Area, a view similar to this should be seen, with a lot of new shortcuts to these different decoupled areas that had been mentioned.

### Edit Component Update

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=369" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Not much has changed in the Component in regards to where what is located, but how to interact with it has been moved. For example, The Component Updates has a button 'Edit component update for this Joomla component', and if it is clicked, it is going to ask if everything is saved before you continue. [00:06:30](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h06m30s) If that was done, click 'OK' and it will open the area where the updates can be done. Usually, it was in a model that popped up, and it was possible to change it on the same page. Now you may go to another view and it will do the same. This applies to the Admin View, Custom View, Site View, and everything else.

### Contributor Moved Down - Do On Page

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=420" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Contributors has been moved down so it may be done on the page. But for most of the other Repeatable Fields, it had been moved to their own Tables.

### Moved Component Files And Folders To Joint Table

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=431" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Fields and the Folders had been moved to a joint table. If this 'Edit component files folders for this Joomla component' is selected it will be easy to add some files to the Component or Folders, all found within this Structure as it is explained in the note. The same applies to all the other areas.

### Moved Admin Views To Its Own Tab

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=462" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Admin Views has been moved to its own tab. It may be accessed via the button 'In Settings - edit component admin views for this Joomla component' or via the button 'Linked Admin View-Edit ' [00:07:54](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h07m54s) In Editing the Joomla Component area it is possible to see your changes and from here directly edit the Admin View that has been linked. It will be able to edit the Admin View directly out of your Component area. That is a nice new feature which will come in very handy. [00:08:15](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h08m15s) The new upgrade targets the majority of the changes in the Joomla Component Area. If it happens that we have missed a field during the upgrade by not converting it to the new Sub Form layout; there is a lot of data checks all around JCB at this stage which; when a view is opened, runs through all those Fields, and make sure that it has been changed and converted. [00:08:54](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h08m54s)If by any means you did not get around to open the views; go to the Compiler, and click compile. It does that again, it runs through all the Fields and it makes sure that it is in the right format. Therefore the compiling should work as before.

### New Feature - Translation Checker

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=559" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

One of the new features that have been added is this Translation Checker(Warning) which checks how many strings are within the component and how many were translated for this specific version, if a New language is available for the Admin View, the Admin System View, the Site View, and again for another Language, Admin View, Admin System View, and the Site View. This gives feedback on your progress. This area of JCB is maybe not utilized as much as it can be.  

### Becomes Active If Language Is Setup

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=608" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

It only becomes active if you have got some Language setup. There should be some languages in the Languages area and that component should have been compiled at least once before. [00:10:26](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h10m26s) Because the Language string stored in JCB which is found on the Language Translations, is only generated once it has compiled the Component at least once. Then it links the Component Language strings to JCB and you can translate them into those Languages that you have created.

### Not An Error Only a Miss Configuration

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=648" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The problem regarding the Back-up folder: Because a Backup folder has not been set up for this JCB install. It will say that; if I leave the set to 'Yes' and compile. It will indicate that it could not move that Backup file, because the Temporary folder and the Backup folder are in the same location. That means this is not an error, it is just a miss-configuration. We have not set up the Back-up folder to be separate from the Temporary folder.

### Percentage of Translation Required can be changed

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/MQrLBYhvGyA?start=699" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In the options area of JCB, the percentage of translation required can be changed before a translation is added. Currently, it is set to 50% but you may set the percentage as you like.

That is creating a Component with the new upgraded JCB. Compiled that, and return to the Demo. It may be seen that the component has been built and everything works as expected. [00:12:18](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h12m18s)

If you run into any issues that are related to this upgrade after you have cleared the browser memory, then please open an issue on GitHub. (Note that I am using Firefox 64-bit) We will try to get back to you and see if we can get this resolved. My experience so far is that this upgrade has taken JCB to a very powerful position, where it does not have Repeatable Fields anywhere in the Component. All its Repeatable Fields have been converted and are only Sub Forms. [00:13:19](https://www.youtube.com/watch?v=MQrLBYhvGyA&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h13m19s) We have added some nice shortcuts to these decoupled areas so that it may be accessed directly without going through the Component View. If you want to work on, for example, the Component Dashboard, and you need to make some changes to the dashboard, or you need to work on the Admin Views, you can click on that button below the view and work on the Admin Views without going to the Component directly.

</div>
