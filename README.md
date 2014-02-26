# Ghost HTML5 Boilerplate Theme

A barebones theme for [Ghost](http://github.com/tryghost/ghost/) based on [html5-boilerplate](http://github.com/h5bp/html5-boilerplate/). This theme offers a very basic, unstyled output of your Ghost content to give you a head-start with the theme engine, while implementing the structure and best-practices of HTML5-Boilerplate. The theme also borrows some code from the default Ghost theme [Casper](http://github.com/TryGhost/Casper).

Please note that Ghost is in an early development stage and this theme may adapt as Ghost evolves.

![Screenshot](https://raw.github.com/wiki/jdahdah/ghost-html5-boilerplate/ghost-html5-boilerplate-screencap.png)

## Installing
Download the [latest version](http://github.com/jdahdah/ghost-html5-boilerplate/archive/master.zip) of the Ghost HTML5-Boilerplate Theme and unzip its contents into a folder named whatever you want to call your theme. Put that in the Ghost theme directory:

`[GHOST_DIRECTORY]/content/themes/`

Restart Ghost, then navigate to `Settings` \> `General` in the Ghost admin area. Select your theme from the dropdown menu labeled "Theme" and hit `Save`. Voilà.

## Version
The current master version of Ghost HTML5 Boilerplate is intended for use with **Ghost v0.4 and above** and based html5-boilerplate v4.3.0. Refer to the [releases](http://github.com/jdahdah/ghost-html5-boilerplate/releases) page if you need this theme compatible to an older version of Ghost. Version numbers are matched up to the Ghost release they are compatible with.

## Feedback
Please leave feedback by opening an [issue](http://github.com/jdahdah/ghost-html5-boilerplate/issues) on Github.

## Known Issues
It’s currently not possible in Ghost to implement a CDN for jQuery delivery in the same way it is done in h5bp. The reason is that the system outputs jQuery in the custom tag `{{ghost_foot}}` which must be included in every theme. This is a [known issue](http://github.com/TryGhost/Ghost/issues/1181) that may be resolved in a later version of Ghost.

## Copyright & License

Copyright (c) 2014 Jerome Dahdah - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
