---
autogenerated: true
title: Requirements
layout: page
categories: 
description: test description
---

This page should list the requirements of Fiji on different platforms to solve installation problems easier.

General
-------

Windows
-------

-   Java 3D 1.5.1 is shipped with Fiji and requires **OpenGL 1.3 or higher**. You can use {% include bc content='Plugins | Utilities | Debugging | Test Java3D'%} to test the functionality of Java 3D. If you do not see a rotating cube, install the latest graphics card driver for your system and check its OpenGL version.

Mac OS X
--------

-   **Mac OS X 10.4 or higher** is required. This is due to many plugins needing Java version 1.5 or higher, and Apple does not provide those versions with older Mac OS X versions.

*Note:* This requirement might be lifted in the near future, as OpenJDK will merge the BSD port soon, which includes SoyLatte, a port of the BSD port to MacOSX. A bit of work lies ahead of those efforts, as only early parts of an Aqua UI interface are present, and only the X11 interface is expected to run smoothly.