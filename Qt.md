--
title: Qt
oneline: Cross-Platform App Framework
forum: "http://qt-project.org/forums/viewforum/11/"
techlink: 
tags: cascades, native, blackberry10, qt, playbook

layout: technology
---
{% include common-defs.md %}

### Description
Qt is a cross-platform application and UI framework which can be used for the
development of both Blackberry 10 and Playbook native applications.
Developers can choose to write their software using C++, QML or a mix of both.
QML is a declarative language designed to describe the user interface of a
program: both what it looks like, and how it behaves. It uses JavaScript as a
scripting language, and its syntax resembles that of CSS.

Apart of that, BlackBerry 10 Devices also support [Cascades] for UI development.
[Cascades] leverages the Qt object model, event model, and threading model,
using
QtCore, QtXML, QtSql, QtNetwork and QtSensors.
The [Cascades] UI elements are available through C/C++ bindings and using [QML].

### Developing for the BlackBerry Playbook

Developers willing to create Playbook applications should use the Qt for
Playbook SDK
binaries available at http://github.com/blackberry/Qt/downloads. You can also
choose
to build Qt for Playbook yourself. Instructions on how to do it can be found at
http://qt-project.org/wiki/QNX and
http://qt-project.org/wiki/Building-Qt5-for-the-Playbook.

### Developing for BlackBerry 10

Developers targeting BlackBerry 10 devices have the possibility of choosing to
use either
stock Qt or [Cascades].

* Go to the [Cascades] page if you would like to learn more about it.
Alternatively, see
http://qt-project.org/wiki/QNX for instructions on how to build Qt yourself.

### Support

BlackBerry 10 and Playbook developers interact through two forums:

* Developers using Qt as part of Cascades-centric applications should use
the [Cascades
Forum](http://supportforums.blackberry.com/t5/Cascades-Development/bd-p/Cascades
)
* Developers using Qt as part of Games/Ports of games should use
the [Native
Forum](http://supportforums.blackberry.com/t5/Native-Development/bd-p/native_sdk)
 
### Filing Bugs

Defects or requests for enhancement can be submitted through the [DevZone
JIRA](https://www.blackberry.com/jira/secure/Dashboard.jspa),
which is monitored by members of the BlackBerry DevRel team.

BlackBerry 10 and Playbook use Qt from the upstream community at
[Gitorious/qt](http://qt.gitorious.org/qt);
issues that come from there can also in the corresponding
[BugReports](http://bugreports.qt-project.org)