Easyconf
========

This is a fork of easyconf from [easyconf.sourceforge.net](http://easyconf.sourceforge.net/ "Easyconf on Sourceforge")
with some minor changes to some of the modifiers (using protected in place of private so class can be subclassed)
and moves some object creation to a separate protected member to accommodate overriding the
type of class created and used in a super method without having to recreate the entire method.

