Features
========
 - shell prompt
 - cd, pwd, exit/quit, launching
 - usual shell stuff
 - job control (background processes)
 - Uses [linenoise](https://github.com/antirez/linenoise) for a good input prompt.

Bonus
=====
 - pinfo
 - Tilde expansion of shell (ls ~/bin -> ls <PATH>/bin)

 Resources
 =========

 - GNU's [Implementing a Job control shell](https://www.gnu.org/software/libc/manual/html_node/Implementing-a-Shell.html) 
 was pretty much the _only_ resource on the internet which I could find that accurately
 describes the intricacies of setting up a pipeline correctly with groups, and making
 sure things get killed in a pipeline together. Awesome reference.
