
==========
checkrepos
==========

 - a utility that helps you manage many git repositories.


This is a "read-only" git utility.

Working environment:
--------------------
    The toplevel of the git repositories are one level down from
    where you run checkrepos.

Output:
-------
    A list of git repos, with indications of which ones have:
         - changes in the working directory but not in index
         - changes in index
         - commits locally but not at remote
         - commits at remote but not locally.
