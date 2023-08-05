# __NOTES__

This is a simple bash script that can be used to save short notes (50 char max) using simple commands.

A cron job periodically vacates notes older than 4 weeks old.

Usage: notes [_add_|_view_]

## Features
- [x] Add a note.
- [x] View all notes.
- [x] Automatically vacate stale notes.
- [ ] Prompt which notes to vacate and which ones to keep.
- [ ] Save notes into a file incase the database fails.
- [ ] Delete individual notes.

## TODO: 
An install script that:
- Ensures that all dependencies are installed before attempts to run the script.
- Adds the script path to the PATH variable or install in /usr/bin.
- Creates a mysql user and add their password to $HOME/.my.cnf for a passwordless login.
- Sources the tables.sql file to set up the database tables and columns.
- Add a cron job to vacate stale notes.