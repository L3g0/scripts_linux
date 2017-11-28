# git operations using private-key stored on custom location(not-default)
`ssh-agent $(ssh-add <private-ssh-key-path>; git clone <git-directory-path>)`
# Update the clone repos. config and set url to `git` from `https` to allow for commit via ssh-key
 `git remote set-url origin git@github.com:<user-name>/<project-name>.git`
