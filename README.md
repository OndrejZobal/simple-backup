# What is simple-backup?
`simple-backup` is a really simple bash script. It creates a backup of file or data stream and saves it to a given directory. Then it will check if the given directory contains more backups than specified and if so, deletes the oldest ones, based on the time-stamp in their file name.

This program is primarily ment to be used with cron. As seen in `usecase.cron`.

# How do I use simple-backup?
To see all available options you can use `simple-backup -h`. For a real world example see `usecase.cron`.

# Can I contribute?
Sure.

# Warranty
From my experience the program seems to be working as expexted but even so **I offer absolutely no warranty**! Use at your own risk.

# License
The project is licensed under GNU AGPL v.3 or later. See [license](LICENSE).

