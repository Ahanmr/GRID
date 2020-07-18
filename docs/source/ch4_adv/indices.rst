Customize Vegetation Indices
============================

Will be done by the end of July 2020.

using a relative path to the local file: link_.

.. _link: custom_index.ipynb



git filter-branch --env-filter '
    oldname="James Chen"
    oldemail="chun-pengc.chen@wsu.edu"
    newname="James Chen"
    newemail="chun-peng.chen@wsu.edu"
    [ "$GIT_AUTHOR_EMAIL"="$oldemail" ] && GIT_AUTHOR_EMAIL="$newemail"
    [ "$GIT_COMMITTER_EMAIL"="$oldemail" ] && GIT_COMMITTER_EMAIL="$newemail"
    [ "$GIT_AUTHOR_NAME"="$oldname" ] && GIT_AUTHOR_NAME="$newname"
    [ "$GIT_COMMITTER_NAME"="$oldname" ] && GIT_COMMITTER_NAME="$newname"
    ' HEAD
