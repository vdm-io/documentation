<div style="text-align: justify">

# TEMPLATE SETUP

### Creating Templates

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/khxKeeubhiY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In the previous tutorial, we looked at setting up templates and layouts to a site view. Loaded inside the site view is 'preacherpanel', 'preachersmall','preacherbox'. If you go to Templates, you may see how this works.

### New - Copying Templates

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/khxKeeubhiY?start=27" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Click on new to start with a new template. (An old one may be copied by selecting the template you would like to copy.) Click on Batch. There is a copy feature; click process, and it will be copied. [00:00:49](https://www.youtube.com/watch?v=khxKeeubhiY&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h00m49s) Open Preacher panel. (Preacher panel is an HTML area.) If PHP is preferred, go into the PHP and out again. Text placeholders may be added helping us to ensure the text itself is translatable. You can use normal English text. (See video.)

### Language String

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/khxKeeubhiY?start=80" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Component Builder will add these strings to the language file for you. You don't need to be concerned; it only does the British English language file. If you need to add more languages, check the documentation of adding languages to a third-party extension and do the same implementation. [00:01:44](https://www.youtube.com/watch?v=khxKeeubhiY&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h01m44s) At Layouts Code Snippets you can add layouts to the template by using any of the snippets. You can add other templates to it, and you can use templates inside of templates as well as layouts. The behavior is more or less the same as in site view.

### Adding Custom Script/Code to Template

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/khxKeeubhiY?start=133" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

You have a snippet box that you can make use of by adding script quickly to your page. If we go to the code the script looked at in the preacher panel is the same script here. (See video.)

### Adding JavaScript To Template

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/khxKeeubhiY?start=166" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In your details tab in the template area, there is a side note. You can add JavaScript with your normal script tags. [00:03:13](https://www.youtube.com/watch?v=khxKeeubhiY&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h03m13s) It will be loaded into the page through this little snippet. You still have access to all the global 'this' field values. (See video.) [00:03:35](https://www.youtube.com/watch?v=khxKeeubhiY&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h03m35s) You can access them easily. The same kind of conventions as setting up a site view is used to set up a template, except that this is not the main view. It is a template used somewhere in a main view through adding the code snippet with Joomla class get template method. [00:04:02](https://www.youtube.com/watch?v=khxKeeubhiY&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m02s) Load template as the method used with that name. It adds it to your component site view and adds the code to it and everything else. [00:04:29](https://www.youtube.com/watch?v=khxKeeubhiY&list=PLQRGFI8XZ_wtGvPQZWBfDzzlERLQgpMRE&t=00h04m29s)

</div>
