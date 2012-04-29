<A name="toc1-0" title="Workflow Tools" />
# Workflow Tools

These tools are for streamlining git based workflows that I find useful.

<A name="toc1-5" title="gitwrench" />
# gitwrench

Given a path, find subdirectories that are git repositories and analyze them for push, commit, and remotes status.

<A name="toc1-10" title="git-upstream" />
# git-upstream

Fetch upstream and rebase. Assumes master locally and upstream/master as the new changes to rebase over.

<A name="toc2-15" title="Dependencies" />
## Dependencies

* python-git or git-python, depending on your distro
* http://code.google.com/p/pythonfutures/

<A name="toc2-21" title="To Add" />
## To Add

* automate taking action such as fetches and pulls
* support tracking branches other than master.
* Detect untracked files - if git-python is new enough.
* Integrate with submodules somehow.
* detect remote head updated status for git-svn
* work with mercurial
* work with bazaar
* work with svn directly
