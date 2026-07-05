This is just a demo repository to test some of the git features. 

# Git fork
## Forking from Github's UI   
 * you can make a fork directly from github UI 

## Forking by command line
 * or you can add a new remote to your fork see (https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/configuring-a-remote-repository-for-a-fork ) 
 * then you should sync your fork (https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork#syncing-a-fork-branch-from-the-web-ui ) 

# Git merge to a forked branch


# Git rebase with squash
## First squash commits on your feature branch ( berefore merging / rebasing on main )
    git rebase -i commit_id ( where commit_id is the last commit that does not belong to your feature branch) - based on this commit you've based your feature
    git rebase -i master ( this is another option) 

## Then mark with squash ( instead of pick ) all the commits and save the buffer

## A new buffer with a commit message will be prompted for your editing
At this point your squash is done ... do your rebasing in main if needed


