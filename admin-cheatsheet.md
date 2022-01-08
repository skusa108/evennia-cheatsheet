## Permissions
Account levels:
1. Developers
    - Basically have the same access as superusers except that they do not sidestep the Permission system. Assign only to really trusted server-admin staff since this level gives access both to server reload/shutdown functionality as well as (and this may be more critical) gives access to the all-powerful @py command that allows the execution of arbitrary Python code on the command line.
2. Admins 
    - Can do everything except affecting the server functions themselves. So an Admin couldn’t reload or shutdown the server for example. They also cannot execute arbitrary Python code on the console or import files from the hard drive.
3. Builders
    - Have all the build commands, but cannot affect other accounts or mess with the server.
4. Helpers
    - Almost like a normal Player, but they can also add help files to the database.
5. Players
    - The default group that new players end up in. A new player have permission to use tells and to use and create new channels.

When you puppet a Character you are using your Account-level permission. With the `quell` command you can change so that the Character’s permission takes precedence. `Unquell` reverts back.

### Assinging permissions
`@perm/account Tommy = Developer`
