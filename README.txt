# Workflow Tools

These tools are for streamlining git based workflows that I find useful.

# gitwrench

Given a path (or working directory), find subdirectories that are git repositories and analyze them for push, commit, and remotes status.  Optionally do pushes and pulls.  Integrates partially with git-svn.  Keep up with what changes everyone's been doing on projects you have clones of.  Don't be running old code!

    "I wrenched my git once. Hurt for a few days." - David

# git-upstream

Fetch upstream and rebase. Assumes master locally and upstream/master as the new changes to rebase over.

## Dependencies

* python-git or git-python, depending on your distro
* http://code.google.com/p/pythonfutures/

Or if you're so inclined, you can just install everything in `requirements.pip`.

## To Add

* support tracking branches other than master.
* Detect untracked files - if git-python is new enough.
* Integrate with submodules somehow.
* detect remote head updated status for git-svn
* work with mercurial
* work with bazaar
* work with svn directly
