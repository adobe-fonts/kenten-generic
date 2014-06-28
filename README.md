Kenten Generic
====

Overview
----
Kenten Generic is a special-purpose OpenType font. This open source project provides all of the source files that were used to build this OpenType font by using the AFDKO *makeotf* tool.

Getting Involved
----
Send suggestions for changes to the Kenten Generic project maintainer, lunde@adobe.com, for consideration.

Building
====

Pre-built font binaries
----
The installable font resources (font binaries) are not part of the source files. They are available on [Open@Adobe](https://sourceforge.net/projects/kenten-generic.adobe/files/).


Requirements
----

For building binary font files from source, installation of the [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html) (AFDKO) is necessary. The AFDKO tools are widely used for font development today, and are included in most font editing applications.

Building the fonts
----

The key to building OpenType fonts is *makeotf*, which is part of AFDKO. Information and usage instructions can be found by executing *makeotf -h*.

In this repository, all necessary files are in place for building the OpenType font. For example, build a binary OTF font like this:

    % makeotf -f cidfont.ps -r -ch UniKentenGeneric-UTF32-H

That is all.
