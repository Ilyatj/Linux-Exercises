File                     | Result After Deletion | Explanation
------------------------ | ------------------- | ----------------------------------------------
info.txt (hard link)     | ✅ Remains intact    | Because a hard link is an independent entry to the same inode
info_s.txt (symlink)     | ❌ Broken            | Because it points to the original file's path
