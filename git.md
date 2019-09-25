Local Repository Structure
The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit
image03

Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

Tracked 
Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

Untracked
Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.