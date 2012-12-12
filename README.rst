===========
git-covdiff
===========

This is ...
===========

An utility to support your coverage task.

Determine the missing which appeared newly in latest commit by comparing the hunks of the commit to coverage analyzed.
To use this, first, measure the project coverage at the target revision to generate *.coverage*.

Requirements
============

- coverage >= 3.6b1
- pygit2 >= 0.17.3 (and libgit2 http://libgit2.github.com/ )

I don't test with earlier versions.
