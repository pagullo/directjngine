# DirectJNgine 3.0 is out! #

Check [this link](https://softdevbuilttolast.wordpress.com/2015/03/10/directjngine-3-0-just-released/) to take a look at what's new in DJN 3.0.

You can download DirectJNgine in the [new downloads](http://www.softwarementors.com/directjngine/downloads/) page. For older versions, go to this website's _Downloadas_ area.

To learn how to configure the Spring adapter go to the [Spring-DJN site](https://code.google.com/p/spring-djn/). To see how to configure the CDI adapter, go [here](https://code.google.com/p/jee-djn/).


# What is DirectJNgine? #

_DirectJNgine_ (or _DJN_, for short), is a Java based implementation of the [Ext Direct API](http://extjs.com/blog/2009/05/13/introducing-ext-direct/) for [ExtJs](http://extjs.com).

_ExtJs_ is probably one of the most _powerful and attractive UIs_ for web-based applications, as can be seen [here](http://extjs.com/deploy/dev/examples/desktop/desktop.html), as well as in many other [examples](http://extjs.com/deploy/dev/examples/). _DirectJNgine_ makes it much easier to use the full power of Java business classes with such a powerful front-end, making Java methods _directly callable from the client_.

_DirectJNgine_ is fully feature complete, providing support for all kinds of requests: batched json requests, form posts with file uploads, requests from polling providers, etc.

A detailed _User's Guide_ (more than 40 pages) is part of the distribution. Besides, it runs all of Ext Direct examples distributed with _ExtJs_, located in _examples/direct_, and additional demos are included and discussed in the _User's Guide_.

_DirectJNgine_ is extensively tested, passing more than 140 automated tests for all supported web browsers (see the list below).

For further info, take a look at the _User's Guide_.


# DirectJNgine feature list #
_DirectJNgine_ provides the following features:
  * **NEW in DJN 3.0**: support for connector supporting both CDI and Spring beans as action classes.
  * **NEW in DJN 3.0**: support for ExtJs 5.x
  * DJN 2.3: support for pluggable adapters that will allow integration and injection of Spring beans, CDI beans or whatever you want as/into action classes.
  * DJN 2.2: auto-conversion to arrays to support ExtJs liberality with parameters.
  * DJN 2.2: enhanced date support.
  * DJN 2.2: enhanced support for server side exceptions.
  * DJN 2.1: added support for ExtJs 4.1.x plus additional tests.
  * DJN 2.0: added support for ExtJs 4.0.x
  * DJN 1.3: support for [Google AppEngine](http://code.google.com/appengine).
  * DJN 1.3: support for ExtJs 3.2.x.
  * DJN 1.2: session and application scoped actions.
  * DJN 1.2: access to the current session, servlet context, servlet configuration, etc., from within action methods.
  * NEW in DJN 1.2: support for multiple instances of an action.
  * DJN 1.2: support for ExtJs 3.1.1, which is the new test platform.
  * DJN 1.1: programmatic API definition which allow easier third-party customization.
  * DJN 1.1: main servlet can be used as a base class for easier third-party customization
  * Easy _annotation-based configuration_.
  * Support for _JSON_ requests.
  * Support for _batched JSON_ requests.
  * Support for _Simple Form Post_ requests (no files to upload).
  * Support for _File Upload Form Post_ requests.
  * Support for _PollingProvider_ requests.
  * _Automatic API files generation_, supporting multiple API files.
  * Customization support for JavasScript<=>JSON<=>Java _serialization/deserialization_.
  * _Fully tested_: passes _more than 100 automated tests_, which can be run from the demo WAR.
  * Detailed _User's Guide_: more than 40 pages.
  * _Debug mode_ support.
  * Tested against most popular browsers: the delivery process includes executing all tests and demos against the lastest versions of the following browsers:
    * Internet Explorer.
    * Firefox.
    * Safari.
    * Chrome.
  * Includes several _demos_: provides several demos, and runs all the demos provided by _ExtJs_ in _examples/direct_ (as explained in the _User’s Guide_).
  * Free for commercial projects: LGPL v3 license.
  * **Advanced**: _Multithreaded execution_ of batched requests for better performance.
  * **Advanced**: _API files consolidation_: several APIs can be stored in just one file to reduce communication overhead.
  * **Advanced**: API files _minification_ support: usually reduces api file size in half.
  * **Advanced**: possibility to call public, private, package and protected instance or static methods in public or private classes.
  * **Advanced**: detailed _logging_, to support easy diagnostic of problems.
  * **Advanced**: provides detailed timing information, via logging.

# Support #
[The Ext.Direct support forum](http://extjs.com/forum/showthread.php?t=73027) is the place to go to discuss issues related to _DirectJNgine_

# Get DirectJNgine #
[The downloads page](http://code.google.com/p/directjngine/downloads/list) is the place to go to download _DirectJNgine_ as well as its _User's Guide_.