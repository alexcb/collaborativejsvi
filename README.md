collaborativejsvi
=================

Collaborative vi is based on jsvi (http://gpl.internetconnection.net/vi/) and builds upon firebase's database to perform synchronization between two clients.

This hack only works for n = 2 clients, and will not be developed beyond this point.

Bugs
======

If a new client joins (or refreshes) the text will/may be reset to the initial text

Demo
====

Just clone, and open cvijs.html If you are using chrome, you must use ctrl-[ rather than escape. Firefox on the other hand, will pass along the esc key into the javascript handler.

You can also watch it in action at http://www.youtube.com/watch?v=WiTWdyblAfI

