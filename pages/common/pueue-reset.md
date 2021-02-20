# pueue reset

> Kill everything and reset.
> More information: <https://github.com/Nukesor/pueue>.

- Kill all tasks and remove everything (e.g. logs, status, groups, task IDs):

`pueue reset`

- Kill all tasks and terminate their [c]hildren and reset everything:

`pueue reset -c`

- Reset without asking for confirmation:

`pueue reset -f`