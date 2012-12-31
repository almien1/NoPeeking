NoPeeking
=========

A text editor that works directly with GPG files.

The file is always encrypted while on disk.  Once open, a file
can be quickly saved back to disk, rendering it unreadable without 
the password.

Usage: NoPeeking example.gpg

When a file is first opened, its contents will not be displayed.
This is because it's still encrypted.  To start editing the file,
type its password into the 2nd textbox, and click "Unlock".

At any time, you can stop editing a file by clicking "Lock".
This will save the file to disk (encrypted), and remove it from
view.  To resume editing the file, type the password and click
"Unlock".

The file is automatically locked if it has been left unattended
for a while.

