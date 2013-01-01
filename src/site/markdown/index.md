What is Ajaxterm4j?
====

Ajaxterm4j is a Java port of [Ajaxterm](http://antony.lesuisse.org/software/ajaxterm/), which lets us emulate a terminal on a web browser.

Ajaxterm4j consists of JavaScript that renders the terminal on the client, `XmlHttpRequest` that sends keystrokes and screens back and forth,
and a Java library that launches/manages processes. The library plays a similar role to xterm, except that whereas xterm is
implemented in C and use X for rendering, ajaxterm4j is implemented in Java and uses Ajax/HTML for rendering.

Usage
---

Refer to the javadoc of the `Session` class. Depending on the web framework of your choice, how you intergrate this with your webapp will be different.

Also see the demo webapp application.