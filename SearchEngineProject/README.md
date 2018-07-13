git remote add origin https://github.com/omgacat520/WorkHomeRep.git
git push -u origin master

^THIS IS FOR REMOTE ADDING^


NEEDS 2 PAGES, RESULT AND SEARCH
needs (non-functional) search bar with fluid design,
avoid using media queries, rely on FlexBox and Grid.


TO RECEIVE FILES FROM REMOTE REPOSITORY (GitHub)
$ git fetch <remote> Replace remote with URL of gitRepository.

For adding School Remote https://stackoverflow.com/questions/849308/pull-push-from-multiple-remote-locations
https://stackoverflow.com/questions/46915350/got-fatal-branch-master-does-not-exist-in-git

FOR FUTURE SETUPS ON SEPERATE SYSTEMS
Git Pull = Update Local versions

SETUP
cd repo <-- Remember to specify where the git init will place repository for concise file organization within the PC. (also prevents hacking by not allowing remote editing of localized files on ENTIRE pc.)
git init
git remote add origin <url>
git fetch origin
git checkout master