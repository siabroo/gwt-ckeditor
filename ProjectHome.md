This project aims to wrap CKEditor (http://ckeditor.com/) with GWT

You can find a quick start guide in the [wiki](http://code.google.com/p/gwt-ckeditor/w/list).

Sample : http://apps.axeiya.com/TestCK/

You can now use gwt-ckeditor with Maven : [Maven Users](http://code.google.com/p/gwt-ckeditor/wiki/MavenUsers)

### v1.1 ###
_Work in progress_

Changes (most probably)
  * update CKEditor to the latest version
  * Fix major bugs
  * Adds user-wanted enhancements (plugin support, etc.)

### v1.0 ###
gwt-ckeditor is now built on Maven. The major release 1.0 is just the mavenization of the projet.

### v0.4 ###
Changes
  * Add 

&lt;FORM&gt;

 interoperability
  * Add setText() support event if the editor isn't attached
  * replace setText and getText by setHTML and getHTML (setText and getText are deprecated)
  * Add tabIndex support
Issues fixed
  * http://code.google.com/p/gwt-ckeditor/issues/detail?id=8&can=1
  * http://code.google.com/p/gwt-ckeditor/issues/detail?id=11&can=1
  * http://code.google.com/p/gwt-ckeditor/issues/detail?id=12&can=1
  * http://code.google.com/p/gwt-ckeditor/issues/detail?id=13&can=1
  * http://code.google.com/p/gwt-ckeditor/issues/detail?id=14&can=1

Special thanks to Emmanuel (welcome to its new blog http://www.gwt-france.fr/) for his job on this version.
Thanks to every defect submitters, alowing us to improve this product.

### v0.3 ###
Changes
  * Fixing issues on multiple custom toolbar and attach/detach editor
  * Adding entities and enter mode support

### v0.2 ###
Changes
  * Adding some options to configuration
  * Adding Save handling when the user click on the Save button
  * Fixing major issues on CKEditor and CKConfig classes