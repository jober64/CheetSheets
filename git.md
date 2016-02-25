# Git Cheat Sheet

## Patching

    git format-patch <branch-name>
    Create a patch for each commit contained in the current branch but not in <branch-name>. You can also specify a commit ID instead of <branch-name>.

    git am < <patch-file>
    Apply a patch to the current branch.
