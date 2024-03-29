# Overview

For this project I wanted to write a revit plugin using c#. Revit is a software that is used heavily in the AEC industry. I've been able to use plugins for this software quite frequently but I've had no experience coding one. For this I wanted to do something super basic that would selecte all the walls and get quantity takeoffs for it, specifically the length and the height of the wall so it would then calculate how many studs we need as well as sheetrock boards. 

My vision for the project would be to eventually expand the functionality of it and include cubic yards of concrete, roofing, and basically in the end produce a full fledge estimate just based off the model

Demo Video: https://www.loom.com/share/7e19bb18bd0a4f4c8f33d07798b1dcea?sid=af04cc5d-9c8c-492f-b06b-66242b90d254

# Development Environment

To get this project working I used Visual Studio Community with a simple C# class template. Additionally I used a lot of Revit API commands, classes, and methods. This was my first time ever using community and I originally just thought it was part of the greater visual studio code but it was nice to switch into community and it was very familiar.

# Useful Websites

AutoDesk: https://www.autodesk.com/support/technical/article/caas/tsarticles/ts/7JiiE4UoWHaTjxzuF754mL.html
Revit plugin from scratch: https://www.youtube.com/watch?v=sjQ-k8Z7T04
How to write a plugin for Revit: https://www.youtube.com/watch?v=ulvaJP4kjKE&t=158s
Revit API Docs: https://www.revitapidocs.com/

# Future Work

For this project, It doesn't work. I need to figure out why it's not wanting to load. I followed multiple tutorials online but whenever I try to put it into my revit software it would never load properly and after it would load properly it would never work. So first off I'm going to get it working.

Second thing I'll do is actually do the basic quantitiy takeoffs and figure out how to do that.

Lastly I'll figure out a way to export it into a sheet