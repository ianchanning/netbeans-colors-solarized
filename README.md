Solarized Colorscheme for NetBeans
==============================

Developed by Ethan Schoonover <es@ethanschoonover.com>
Ported to NetBeans by Brian Fenton [https://github.com/fentie]
Updated PHP colors to match Java / SublimeText PHP by Ian Channing [https://github.com/ianchanning]

See the [homepage for the Solarized colorscheme][solarized] for versions for 
Vim, popular terminal emulators and other applications.

If you have come across this colorscheme via the [NetBeans-only repository on 
github][netbeans-solarized-github], see the link above to the Solarized homepage or
visit the [github repository for Solarized][solarized-github].

[solarized]: http://ethanschoonover.com/solarized
[solarized-github]: https://github.com/altercation/solarized
[netbeans-solarized-github]: https://github.com/fentie/netbeans-colors-solarized

Installation
------------

1. Download the NetBeans Solarized repo. Unpack the downloaded file, then manually create a 
   new zip file containing the "config" folder.

2. Open NetBeans, select Preferences, then Import in the lower left. Navigate
   to the zip file you created, check the Netbeans\_Solarized\_Dark and/or 
   Netbeans\_Solarized\_Light box under the Fonts & Colors section. 

3. Restart NetBeans (just to be on the safe side). 

4. To use the new themes, go to Preferences, Fonts & Colors, and select either 
   of the two new themes from the Profile dropdown, and hit OK.

Known Issues
------------

Do not use the archive program built into Windows XP to create the zip file
in step 1. It does not support file paths longer than a certain length, and
that results in some missing preferences. If you are using Windows XP, use
a third party archiver like 7zip (free).

Which Variation?
----------------

Normally there would be a discussion of 16- vs. 256-color versions of Solarized
here, but I've only ported the 16-color version. This color scheme is also not as 
flashy/rich as the Vim ones due to lack of granularity in the NetBeans theme 
preferences.

The Values
----------

The NetBeans color preferences UI supports RGB, HSB, and hex values. I prefer the
RGB versions, which I've copied below for reference. For the full list of colors
specified in other formats, see [the main Solarized home page][solarized]

    SOLARIZED sRGB
    --------- -----------
    base03      0  43  54
    base02      7  54  66
    base01     88 110 117
    base00    101 123 131
    base0     131 148 150
    base1     147 161 161
    base2     238 232 213
    base3     253 246 227
    yellow    181 137   0
    orange    203  75  22
    red       220  50  47
    magenta   211  54 130
    violet    108 113 196
    blue       38 139 210
    cyan       42 161 152
    green     133 153   0

License
-------
Copyright (c) 2011 Ethan Schoonover

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
