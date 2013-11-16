tagcloud
========

Inspirating by the plugin with the same name, this module will generate a tag cloud with all the words indexed on your website.

- It's specially designed for front AND back end
- It's using an internal cache system, allowing it to reduce the time of rendering ( up to 40 times faster )
- let you easily play with the regex to filter the words
- use templates, totally customizable

This module is based on the great plugin of Johann Knechtel and Arnoud http://dev.cmsmadesimple.org/projects/tagcloud and it's improved in many way with the advantage of the modules API

Exemple of use : 
--------------------------------------

{TagCloud}

{TagCloud number=10 min_px=5 max_px=50 template='mytemplate' resultpage='pageresult'}



List of parameters
--------------------------------------
- (optional) lang="en_US" - obsolète - Remplace le langage courant qui est utilisé pour sélectionner les chaînes traduites. Plus utilisé depuis version 1.11
- (optional) template="" - Will override the template used for the renderer
- (optional) number="30" - Will override the number of tag displayed
- (optional) resultpage="" - Allow you to specify the alias of the page where displayed the results when user clicks on a tag. Can be either the alias or the Id of the page
- (optional) algo="log" - Let you choose the algorithm of displaying
    "log" : used by default, it's a natural logarithm function.
    "linear" : the size of a tag will be really proportional to its counter. 
    
Demonstration
--------------------------------------

you can test this module on my [website](http://www.furie.be/)


Download
--------------------------------------
You can download CmsMadeSimple on [this page](http://www.cmsmadesimple.org/downloads/)

You can download the module on (TODO)