WorldWideWeb distributed code


See the CERN copyright . This is the README file which you get when you unwrap one of our tar files. These files contain information about hypertext, hypertext systems, and the WorldWideWeb project. If you have taken this with a .tar file, you will have only a subset of the files.
THIS FILE IS A VERY ABRIDGED VERSION OF THE INFORMATION AVAILABLE ON THE WEB. IF IN DOUBT, READ THE WEB DIRECTLY. If you have not got any browser installed, do this by telnet to info.cern.ch (no username or password).


Archive Directory structure


Under /pub/www, besides this README file, you'll find bin, src and doc directories. The main archives are as follows:

src/WWWLibrary_v.vv.tar.Z
    The W3 Library. All source, and Makefiles for selected systems.

src/WWWLineMode_v.vv.tar.Z
    The Line mode browser - all source, and Makefiles for selected systems. Requires the Library .

src/WWW/LineModeDefaults_v.vv.tar.Z
    The on-line doucmnetation for the line mode browser, which you may still want if you get the program as binary. A subset of the full source above.

src/WWWNextStepEditor.tar.Z
    The Hypertext Browser/editor for the NeXT -- source and binary.

src/WWWDaemon_v.vv.tar.Z
    The HTTP daemon, and WWW-WAIS gateway programs. Source.

doc/WWWBook.tar.Z
    A snapshot of our internal documentation - we prefer you to access this on line -- see warnings below.

bin/xxx/bbbb
    Executable binaries of program bbbb for system xxx. Check what's there before you bother compiling. (Note HP is called "snake")


Generated Directory structure


The tar files are all designed to be unwrapped in the same (this) directory. They create different parts of a common directory tree under that directory. There may be some duplication. They also generate a few files in this directory: README.*, Copyright.*, and some installation instructions (.txt).


NeXTStep Browser/Editor


The browser for the NeXT is those files contained in the application directory WWW/Next/Implementation/WorldWideWeb.app and is compiled.Whe you install the app, you may want to configure the default page, WorldWideWeb.app/default.html. These must point to some useful information! You should keep it up to date with pointers to info on your site and elsewhere. If you use the CERN home page note there is a link at the bottom to the master copy on our server. See Installation instructions.


Line Mode browser


Binaries of this for some systems are available in /pub/www/bin/ .
. If the binary exists for your system, take that and also the /pub/www/WWWLineModeDefaults.tar.Z. Unwrap the documentation, and put (link) its directory into /usr/local/lib/WWW on your machine. Put the www executable into your path somewhere, and away you go.

If no binary exists, procede as follows. Take the source tar file WWWLineMode_v.vv.tar.Z , uncompress and untar it. You will then find the line Mode browser in WWW/LineMode/Implementation/... (See Installation notes ). Do the same thing (in the same directory) to the WWWLibrary_v.cc.tar.Z file to get the common library.

You will have an ASCII printable manual in the file WWW/LineMode/Defaults/line-mode-guide.txt which you can print out at this stage. This is a frozen copy of some of the online documentation.

Subdirectories to WWW/LineMode contain Makefiles for systems to which we have already ported. If your system is not among them, make a new subdirectory with the system name, and copy the Makefile from an existing one. Change the directory names as needed. PLEASE INFORM US OF THE CHANGES WHEN YOU HAVE DONE THE PORT. This is a condition of your use of this code, and will save others repeating your work, and save you repeating it in future releases.

Whe you install the browsers, you should configure the default page. This is /usr/local/lib/WWW/default.html for the line mode browser. This must point to some useful information! You should keep it up to date with pointers to info on your site and elsewhere. If you use the CERN home page note there is a link at the bottom to the master copy on our server.

Some basic documentation on the browser is delivered with the home page in the directory WWW/LineMode/Defaults. A separate tar file of that directory (WWWLineModeDefaults.tar.Z) is available if you just want to update that.

The rest of the documentation is in hypertext, and so wil be readable most easily with a browser. We suggest that after installing the browser, you browse through the basic documentation so that you are aware of the options and customisation possibilities for example.


Viola browser for X11


Viola is an X11 application for reading global hypertext. If a binary is available from your machine, in /pub/www/bin/.../viola*, then take that and also the Viola "apps" tar file which contains the scripts you will need.
To generate this from source, you will need both the W3 library and the Viola source files. There is an Imakefile with the viola source directory. You will need to generate the XPA and XPM libraries and the W3 library befere you make viola itself.


Documentation


In the /pub/www/doc directory are a number articles, preprints and guides on the web.
See the online WWW bibliography for a list of these and other articles, books, etc.

The archive /pub/www/doc/WWWBook.tar.Z is an extract of the text from the WorldWideWeb (WWW) project documentation.

This is a snapshot of a changing hypertext system. The text is provided as example hypertext only, not for general distribution. The accuracy of any information is not guaranteed, and no responsibility will be accepted by the authors for any loss or damage due to inaccuracy or omission. A copy of the documentation is inevitably out of date, and may be inconsistent. There are links to information which is not provided in that tar file. If any of these facts cause a problem, you should access the original master data over the network using www, or mail us.


Servers


The Daemon tar file contains (in this release) the code for the basic HTTP daemon for serving files, and also for the WWW-WAIS gateway. To compile the WAIS gateway, you will need [a link to] a WAIS distribution at the same level as the WWW directory.


General


Your comments will of course be most appreciated, on code, or information on the web which is out of date or misleading. If you write your own hypertext and make it available by anonymous ftp or using a server, tell us and we'll put some pointers to it in ours. Thus spreads the web...

Tim Berners-Lee
WorldWideWeb project
CERN, 1211 Geneva 23, Switzerland
Tel: +41 22 767 3755; Fax: +41 22 767 7155; email: timbl@info.cern.ch