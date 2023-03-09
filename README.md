# Micro.blog Plugin - Glossary
A Micro.blog plugin that adds the capability to create a custom glossary for use in posts

This plugin is built for Micro.blog by [@AndySylvester](https://micro.blog/andysylvester) (also at [Andy Sylvester's Web](https://andysylvester.com/)

### Installing the plug-in

The plugin is avaialble in the Micro.blog Plug-in directory. Log into your Micro.blog account, go to the "Plug-ins" section and click "Find Plug-ins". Install "Glossary".

Once installed, you should see a new Menu entry for "Glossary".

### Using the plugin

The plugin provides two features for users. The first feature is a JSON data file for users to add their glossary entries. This file is a set of key/value entries. where the first item (the key) is the item you include in your post. The second item (the value) is the text that is substituted during the Micro.blog publish process. The second feature is a Hugo shortcode which is used to access the JSON data file.  You can use `{{< glossary key >}}` in your posts, where "key" is one of the glossary entries.

### Example

Here is a set of steps to make updates to the glossary data file glossaryData.json:

First, log into Micro.blog, then click on the Design link in the left navigation menu:

![Glossary Screenshot 01](https://github.com/andysylvester/plugin-glossary/blob/cd224ee0ec834b2655249aeaae4d86bd007af9ea/static/images/GlosaaryPic_01.png)

Next, click on the "Edit Custom Themes" button:

![Glossary Screenshot 02](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_02.png)

Next, click on the Glossary link:

![Glossary Screenshot 03](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_03.png)

Next, click on the data/glossaryData.json link:

![Glossary Screenshot 04](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_04.png)

Add new entries by clicking in the text window. Make sure that you have double-quotes around each item, and to add a comma at the end if you add the item in the middle of the JSON object.

![Glossary Screenshot 05](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_05.png)

I added a new thing called "newItem", then clicked "Update Template" button.

![Glossary Screenshot 06](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_06.png)

Click "Back" button when you are finished editing the JSON object.

![Glossary Screenshot 07](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_07.png)

Add the new thing in a post

![Glossary Screenshot 08](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_08.png)




### Planned Features

* None at this time, but let me know if you have ideas!

### Change Log

**Version 1.0:** Released March 8, 2023
- Initial version of plugin
