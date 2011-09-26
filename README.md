<A name="toc1-0" title="Workflow Tools" />
# Workflow Tools

These tools are for streamlining git based workflows that I find useful.

<A name="toc1-5" title="gitwrench" />
# gitwrench

Note: these assertions are not yet fully implemented :)

Using the configuration file ~/.gitwrench, this program will look immediately under the specified directories for git repositories and check if they are 'out of sync' between master and origin/master.

For each repository it finds, it will check if uncommitted changes are present (untracked files don't count), if no remote master branch exists, if changes have been committed but not pushed to remote master, and finally (if network is accessible) if any commits on the remote master exist.
