# Xamarin.Android bindings for the Samsung S-Pen SDK

A bindings library project for the Samsung S-Pen SDK, so that Samsung S-Pens (i.e. the stylus pen that comes with certain pen-enabled Android phones and tablets from Samsung) can be used with Xamarin.Android applications, and hopefully in the future, Xamarin.Forms applications. The goal is to produce two libraries (DLLs) that will be available as NuGet packages - one for the Pen-Light (Light SDK version), and one for the Pen-Full (Full SDK version).

This project is currently dependent on version 4.1.2 of the SDK (Oct 27 2016).

[Download the Samsung S-Pen SDK now](http://developer.samsung.com/galaxy/pen)

Note that as of 3/18/2017, this is a thoroughly un-tested work-in-progress project, and the bindings for the Full SDK are not complete... so the PenFull project will not build.  Also, I had some problems building the projects in Visual Studio 2017, so I backed down to VS 2015. It may now work fine in VS 2017, but I am doing my development in VS 2015.
