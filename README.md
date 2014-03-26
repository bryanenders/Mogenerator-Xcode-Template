Mogenerator Xcode Template
==========================

An Xcode project template for a Mogenerator target.

Installation
------------
Place *Mogenerator.xctemplate* in **/Library/Developer/Xcode/Templates/Project Templates/Other/** at either the user or root level.

Project Setup
-------------
1. Add a new target to your project in Xcode
2. Select *Mogenerator* from the *Other* category
3. Assign your Core Data entities’ *Class* names in the xcdatamodel
4. Select the Mogenerator scheme and build
5. Drag the newly generated class files (found at {PROJECT_NAME}/Classes) into your project

How to use
----------
Build with the Mogenerator scheme any time you need to update the machine-readable class files.

<p>&nbsp;</p>

* * *

<sup>**NOTE:** [Mogenerator](http://rentzsch.github.io/mogenerator/) must be installed in order for this template to create a useful target.</sup>
