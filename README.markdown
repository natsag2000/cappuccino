Welcome to Cappuccino!
======================

Introduction
------------
Cappuccino is an open source framework that makes it easy to build
desktop-caliber applications that run in a web browser.

Cappuccino is built on top of standard web technologies like JavaScript, and
it implements most of the familiar APIs from GNUstep and Apple's Cocoa
frameworks. When you program in Cappuccino, you don't need to concern yourself
with the complexities of traditional web technologies like HTML, CSS, or even
the DOM. The unpleasantries of building complex cross browser applications are
abstracted away for you.

For more information, see <http://cappuccino.org>.

System Requirements
-------------------
To run Cappuccino applications, all you need is a web browser that understands
JavaScript.

To build Cappuccino itself, please read more here: [Getting and Building the Source](http://wiki.github.com/280north/cappuccino/getting-and-building-the-source>).

If you're using Windows, you'll also need [Cygwin](http://www.cygwin.com/).

Finally, if you want to easily stay up to date with the latest developments
and contribute your work back to the Cappuccino community, you'll want to
[install Git](http://git-scm.com/).

Getting Started
---------------
These instructions are for building a development copy of Cappuccino. If you'd
just like to get started using Cappuccino for your web apps, you should
instead download a pre-compiled copy of Cappuccino from:

  <http://cappuccino.org/download/>

To build Cappuccino from source, check out the most recent stable version from GitHub:

    $ git clone git://github.com/280north/cappuccino.git (git)

or download the zipball of the most recent source code:

  <http://github.com/280north/cappuccino/zipball/master> (zip)

If this is your first build and your system does not have narwhal and jake
installed, run the bootstrap script to install it and all of its dependencies:

    $ ./bootstrap.sh

Then, simply type `jake` from within the root of the Cappuccino directory.
This will build a "release" copy of the frameworks. Typing `jake debug` will
build a debug version.

`jake install` will build Cappuccino and associated tools and install them for general use.

Editors
-------
The Cappuccino TextMate Bundle: <http://github.com/malkomalko/Cappuccino.tmbundle>.

The Cappuccino Xcode Plugin: <http://github.com/rbartolome/xcode-cappuccino>.

Getting Help
------------
If you need help with Cappuccino, you can get help from the following sources:

  - [FAQ](http://cappuccino.org/discuss/faq.php)
  - [Documentation](http://cappuccino.org/learn/)
  - [Wiki](http://github.com/280north/cappuccino/wikis)
  - Mailing Lists:
    - [Objective-J](http://groups.google.com/group/objectivej)
    - [Objective-J Developers](http://groups.google.com/group/objectivej-dev)
  - IRC: irc://irc.freenode.net#cappuccino

If you discover any bugs, please file a ticket at:

  <http://github.com/280north/cappuccino/issues>

License
-------
This library is free software; you can redistribute it and/or modify it under
the terms of the GNU Lesser General Public License as published by the Free
Software Foundation; either version 2.1 of the License, or (at your option)
any later version.

This library is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more
details.

You should have received a copy of the GNU Lesser General Public License along
with this library; if not, write to the Free Software Foundation, Inc., 51
Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA
