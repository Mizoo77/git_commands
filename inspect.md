### INSPECT & COMPARE
*Examining logs, diﬀs and object information*

**git log**

    show the commit history for the currently active branch

**git log branchB..branchA**

    show the commits on branchA that are not on branchB

**git log --follow [file]**

    show the commits that changed file, even across renames

**git diff branchB...branchA**

    show the diﬀ of what is in branchA that is not in branchB

**git show [SHA]**

    show any object in Git in human-readable format
