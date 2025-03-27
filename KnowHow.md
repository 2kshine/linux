# Linux Know How

### Hard Links

> A hard link is an additional directory entry that points to the same inode(storage block which keeps track of the files like permissions, owner, timestamps, etc) of a file. Files are identified by their inode in linux. When you create a file you are giving another name for that file but the contents remains the same. When you delete a file the file's inode and data arent removed from the disk until all the hard links to that inode have been deleted. The second column in ls -l represent hard links.
