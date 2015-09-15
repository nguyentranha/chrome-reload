Chrome-Reload is an [extension](http://code.google.com/chrome/extensions/) for the [Chrome web browser](http://www.google.com/chrome) to allow automatic periodic reloading of a page. It allows the you to configure how often each page reloads and see a count-down until the next load.

This is useful for scenarios such as monitoring constantly changing pages (eg, search results), or for keeping sessions alive in web applications.

# Status #

2014 Update: Please note that Chrome-Reload in the Chrome App Store is no longer owned or maintained by me.

This is the first release of Chrome-Reloader. I've given it a reasonable amount of testing, and are fairly confident that there are no obvious bugs in the Windows version. See Prerequisites (below) for further details.

The Chrome Extension APIs are changing frequently, so there is some chance it may stop working in the future. It is open source, though, so fixed are welcome.

[Release Notes](ReleaseNotes.md) are available.

# Installation #

## Prerequisites ##

You will need to be running a (very) recent version of Chrome. At the time of writing (Nov 2009), this extension has only been tested on Windows, with Chrome 4.0.237.0 (from the Dev Channel).

~~Linux Chrome 4.0.237 is currently broken due to [this bug](http://groups.google.com/group/chromium-extensions/browse_thread/thread/3d3c6e91798f0113)~~

Linux Chrome 4.0.245 works, but does not display the countdown timer.

Linux [Chromium](http://build.chromium.org/buildbot/snapshots/) 4.0.246.0 (31895) does work, but fails to display the count-down timer.

## Download ##


Direct: [Chrome-Reloader.crx](http://chrome-reload.googlecode.com/svn/trunk/releases/chrome-reloader-0.1.1.crx)

## Updates ##

Chrome extensions are automatically updated when new releases are available. Chrome-Reload supports this.

## Problems ##

If you run into a problem, please [raise a new issue](http://code.google.com/p/chrome-reload/issues/list)

# Screenshots #

Chrome-Reload deactivated, showing the menu for reload times:

![![](http://chrome-reload.googlecode.com/svn/trunk/images/screen1-small.png)](http://chrome-reload.googlecode.com/svn/trunk/images/screen1.png)

Chrome-Reload active, showing the time until the next reload:

![![](http://chrome-reload.googlecode.com/svn/trunk/images/screen2-small.png)](http://chrome-reload.googlecode.com/svn/trunk/images/screen2.png)

Closeup of the reload timer:

![![](http://chrome-reload.googlecode.com/svn/trunk/images/countdown-magnified.png)](http://chrome-reload.googlecode.com/svn/trunk/images/countdown-small.png)

