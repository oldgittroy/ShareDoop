# ShareDoop
Data Science Experiments on SharePoint

About
======

Set up the environment

1.  First configure the Hadoop cluster:
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Foldgittroy%2FShareDoop%2Fmaster%2FAzureHDITemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

2.  Second, install the edge related PaaS componets:
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Foldgittroy%2FShareDoop%2Fmaster%2FAzureHDITemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

3.  Third, install the Storage compoents
<a ref="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Foldgittroy%2FShareDoop%2Fmaster%2FAzureHDITemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>



Metadata Classification System


Migration Analyisis System


Concepts
=========

Lambda Architecture

*  Batch Layer
*  View Layer
*  Speed Layer

Edge Architecture

Storage ARchitecture


History
=======
Around 2010 I was intrigued by the algorithms and systems used to extract information from the Enron eamils.  At the time I was working at a SharePoint expert and decided to attempt to build a VM with both applications installed.  After some time I managed to construct a VM with SharePoint 2010 and a semi-stable build of Hadoop for Windows.  My VM included Eclipse and I proceeded to implement a few map/reduce jobs.  Originally I had intended to use this chimera to build a metadata classification system, in the spirit of the Enron email analysis.  Unfortunately my cocept was not well recieved and I gave in to despair as many of my colleagues said "Hadoop is all hype" or "There just isn't a market for this technology".  So as my first read data science project my goal is to use the best of the cloud and the best of data science to rebuild my dream.


ToDo
=====
* Implement machine learning 
* 