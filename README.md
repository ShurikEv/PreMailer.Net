# PreMailer.Net [![Build Status](http://ci.milk.sh/app/rest/builds/buildType:\(id:bt4\)/statusIcon)](http://ci.milk.sh/project.html?projectId=project3&tab=projectOverview&guest=1)

C# Library for moving CSS to inline style attributes, to gain maximum E-mail client compatibility.

Usage
---------

    string htmlSource = File.ReadAllText(@"C:\Workspace\testmail.html");
    
    PreMailer pm = new PreMailer();
    
    string premailedOutput = pm.MoveCssInline(htmlSource, false);

Installation
----------
**NuGet**: [PreMailer.Net](http://nuget.org/List/Packages/PreMailer.Net)



Credits
-------

* [The Dynamic Programmer](http://blog.dynamicprogrammer.com/2008/01/20/CSSParserClassInNET.aspx) - For his CSS parser
* [Fizzler](http://code.google.com/p/fizzler/)
