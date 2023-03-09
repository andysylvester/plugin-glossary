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

![Glossary Screenshot 01](https://raw.githubusercontent.com/andysylvester/plugin-glossary/main/static/images/Glossary01.png?raw=true)

### Planned Features

* None at this time, but let me know if you have ideas!

### Change Log

**Version 1.0:** Released March 8, 2023
- Initial version of plugin
