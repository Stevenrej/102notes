Class 3 NOTES!


Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

Centralized Version Control

This system entails a single server storing all changes and file versions, which can be accessed by various clients.

Distributed Version Control

To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

So, what is Git?
Snapshots
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

States
Files in Git can reside in three main states: committed, modified and staged.
Committed
Data is securely stored in a local database
Modified
File has been changed but not committed to the database
Staged
Flagged a file’s changed version to be committed in the next snapshot

[Back to Home](https://stevenrej.github.io/reading-notes/)
