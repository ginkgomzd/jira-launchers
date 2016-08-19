# jira-launchers
personal shortcuts to jira filters

## usage
run from a terminal or command-prompt to open with your system browser.

 * jira key-99 - opens an issue
 * jira key - opens a project
 * jira sprint key - uses the earliestUnreleasedVersion() jql function to load the active release in a project, or all projects if none given.
 * create aliases for your saved filters
 
## depends
on xdg-open http://linux.die.net/man/1/xdg-open

##Install
drop this somewhere in your path.
my system uses /usr/local/bin.

### Mac
Could use some help here, since I don't use macs. Might need a replacement for xdg-open. It might be that "open" is the same as xdg-open.
http://alvinalexander.com/mac-os-x/exec-unix-shell-script-mac-finder-execute-click
https://superuser.com/questions/4368/os-x-equivalent-of-windows-run-box#4383

## Configure
* set jira_host to your jira instance url
* alias filter ids in jira_filter()
* adjust e.g. order by's in ..._jql() functions
* build your own commands in jira_cmds() (watch out for filter alias name collissions, which take precedence)

