
`close #47`

https://help.github.com/articles/closing-issues-via-commit-messages/


Closing an issue in the same repository

To close an issue in the same repository, use one of the keywords in the list
below followed by a reference to the issue number in the commit message. For
example, a commit message with Fixes #45 will close issue 45 in that
repository once the commit is merged into the default branch.

If the commit is in a non-default branch, the issue will remain open and the
issue will be referenced with a tooltip. If the commit is force pushed to the
default branch and already existed on another branch, the issue will remain
open.

# Keywords for closing issues

The following keywords will close an issue via commit message:

    close
    closes
    closed
    fix
    fixes
    fixed
    resolve
    resolves
    resolved

# Closing an issue in a different repository:

To close an issue in another repository, use the
`username/repository#issue_number` syntax, as described in "Autolinked
references and URLs".

For example, including Closes `example_user/example_repo#76` will close the
referenced issue in that repository, provided you have push access to that
repository.

# Closing multiple issues

To close multiple issues, preface each issue reference with one of the above
keywords.

For example, This closes #34, closes #23, and closes
example_user/example_repo#42 would close issues #34 and #23 in the same
repository, and issue #42 in the "example_user/example_repo" repository.
