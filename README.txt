=== Highslide4WP ===
Contributors: mg12
Donate link: http://www.neoease.com/plugins/
Tags: highslide, image, emotes, smiley
Requires at least: 2.5
Tested up to: 2.7
Stable tag: 2.0

Easy to use Highslide popups on WordPress.

== Description ==

This plugin allows you easily to make [Highslide](http://highslide.com/) popups on WordPress.

这个插件助你在 WordPress 中轻易地使用 [Highslide](http://highslide.com/) 弹出窗口。

= Supported Languages: =
* US English/en_US (default)
* 简体中文/zh_CN (translate by [mg12](http://www.neoease.com/))

== Installation ==

1. Unzip archive to the '/wp-content/plugins/' directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

= emoticons: =
In 'comments.php' file add the following scripts: `<?php highslide_emoticons(); ?>` (Close the emotion window when somebody select a smiley.) OR `<?php highslide_emoticons(true); ?>` (Holds the emotion window open when somebody select a smiley.)

== Screenshots ==

1. Highslide4WP buttons on WRITE page.
2. Highslide image dialog.
3. Emoticons popup on single pages.

== Changelog ==

****

    VERSION DATE       TYPE   CHANGES
    2.0     2008/12/18 NEW    Compatible with WordPress 2.7.
    1.6.3   2008/10/27 FIX    Correct warning.
                       NEW    Added 'static' argument to 'highslide_emoticons()' method.
    1.6.2   2008/09/08 FIX    Correct cursor position.
                       FIX    Display dialogs over select lists in IE6.
                       FIX    Display icons without black border in IE6.
                       MODIFY Upgrade to Highslide JS 4.0.5.
                       MODIFY Using the highslide-with-html.packed.js version.
    1.6.1   2008/09/04 NEW    Added localization support.
                       NEW    Added Simplified Chinese language support.
                       REMOVE Discard iciba Daily Sentence toy.
    1.6     2008/09/01 FIX    Rewrite code with a better style.
                       NEW    Added emoticons toy.
                       NEW    Added iciba Daily Sentence toy.
                       MODIFY Upgrade to Highslide JS 4.0.3.
    1.5     2008/05/03 NEW    Compatible with TinyMCE 3.0.
    1.0     2008/03/02 NEW    Support Highslide image.
                       NEW    Works for TinyMCE.
                       NEW    Powered by Highslide JS 3.3.12.
