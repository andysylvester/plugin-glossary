# Micro.blog Plugin - Glossary
A Micro.blog plugin that adds the capability to create a custom glossary for use in posts

This plugin is built for Micro.blog by [@AndySylvester](https://micro.blog/andysylvester) (also at [Andy Sylvester's Web](https://andysylvester.com/))

### Installing the plug-in

The plugin is avaialble in the Micro.blog Plug-in directory. Log into your Micro.blog account, go to the "Plug-ins" section and click "Find Plug-ins". Install "Glossary".

Once installed, you should see a new Menu entry for "Glossary".

### Using the plugin

The plugin provides two features for users. The first feature is a JSON data file for users to add their glossary entries. This file is a set of key/value entries. where the first item (the key) is the item you include in your post. The second item (the value) is the text that is substituted during the Micro.blog publish process. The second feature is a Hugo shortcode which is used to access the JSON data file.  You can use `{{< glossary key >}}` in your posts, where "key" is one of the glossary entries.

### Detailed install and use instructions 

First, log into Micro.blog, then click on the Plugins link in the left navigation menu:

![Glossary Screenshot 01](https://github.com/andysylvester/plugin-glossary/blob/bbe4e701c0dcd9da0f277db1c99861df746aca7c/static/images/GlossaryPic_20.png)

Next, click on the "Find Plugins" button:

![Glossary Screenshot 02](https://github.com/andysylvester/plugin-glossary/blob/b15f2b7b477dfef70c2816929218d30113f8e240/static/images/GlossaryPic_27.png)

Next, click on the Install button for the Glossary plugin:

![Glossary Screenshot 03](https://github.com/andysylvester/plugin-glossary/blob/b15f2b7b477dfef70c2816929218d30113f8e240/static/images/GlossaryPic_23.png)

Next, click on the Settings button for the Glossary plugin from your list of plugins:

![Glossary Screenshot 04](https://github.com/andysylvester/plugin-glossary/blob/b15f2b7b477dfef70c2816929218d30113f8e240/static/images/GlossaryPic_21.png)

A new text field will appear:

![Glossary Screenshot 05](https://github.com/andysylvester/plugin-glossary/blob/a8887b26afc8657192f656792fce76a2aafc72e3/static/images/GlossaryPic_28.png)


Paste in a JSON object like at https://github.com/andysylvester/plugin-glossary/blob/main/data/glossaryData.json

Add new entries or edit old entries by clicking in the text window, then start typing/editing. Make sure that you have double-quotes around each item, and to add a comma at the end if you add the item in the middle of the JSON object.

I added a new thing called "newItem"

![Glossary Screenshot 06](https://github.com/andysylvester/plugin-glossary/blob/a8887b26afc8657192f656792fce76a2aafc72e3/static/images/GlossaryPic_25.png)

Click "Update Settings" button to save your changes. The browser will return to the Plugins page.

![Glossary Screenshot 07](https://github.com/andysylvester/plugin-glossary/blob/a8887b26afc8657192f656792fce76a2aafc72e3/static/images/GlossaryPic_26.png)

Create a post and include one of the glossary items in the post using the glossary shortcode. The general form of the shortcode is {{ glossary newItem }}, where newItem is an entry in the glossary. This post shows several shortcode examples:

![Glossary Screenshot 08](https://github.com/andysylvester/plugin-glossary/blob/96ba17c39adb8a871c7039f1a2182ba488c67047/static/images/GlosaaryPic_08.png)

Publish the post, then check it on your Micro.blog site. The Preview button will not show the inserted glossary entry. 

Have fun!


### Planned Features

* None at this time, but let me know if you have ideas!

### Change Log

**Version 1.1.0:** Released March 18, 2023
- Working version of plugin using JSON field definition to allow user to add/change glossary entries

**Version 1.0.1:** Released March 13, 2023
- Addition of JSON field definition to plugin.json, update to version number

**Version 1.0:** Released March 8, 2023
- Initial version of plugin
