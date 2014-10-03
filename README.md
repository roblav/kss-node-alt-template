kss-node-alt-template
=====================

This is an alternative **template** for [kss-node](https://github.com/hughsk/kss-node) styleguide.
"kss-node" is a NodeJS implementation of [Knyle Style Sheets](https://github.com/kneath/kss) (KSS).
kss-node enables us to generate a styleguide for CSS, it supports LESS, SASS and Stylus etc.

Demo
----
**[Example Styleguide](http://roblav.github.io/kss-node-alt-template/)**

### Features
* Generating the style guide is automatically from your live CSS keeps your style guide perfectly instep. Removing the issue that is created by manually created style guides which take effort to maintain.
* You can create as many sections of the style that you like which automattically get added to an easy to use sidebar navigation.


Download
--------
**[kss-node-template](https://github.com/roblav/kss-node-alt-template/archive/master.zip)** [zip] or

```
git clone git://github.com/roblav/kss-node-alt-template.git
```

**Note:** This package contains only template files.
You have to install kss-node at first.


How to apply this template
--------------------------
1. Install kss-node. Type `npm install kss` or `npm install -g kss` for global CLI.
2. Download [kss-node-template](https://github.com/roblav/kss-node-alt-template/archive/master.zip) and copy the "template" folder into your working directory.
3. Run `kss-node` command with `--template` option, like below.

```
kss-node <sourcedir> --template path/to/template
```

Credits
--------------------------

[htanjo](https://github.com/htanjo) created this KSS Node template project that initially helpped me to get started on creating my own KSS Node template project.

Check it out here [https://github.com/htanjo/kss-node-template]()https://github.com/htanjo/kss-node-template)

License
-------
This template is under the [MIT License](https://github.com/roblav/kss-node-alt-template/blob/master/LICENSE).
