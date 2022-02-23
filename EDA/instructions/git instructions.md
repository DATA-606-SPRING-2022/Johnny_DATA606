https://www.youtube.com/watch?v=3aKda-oXWc8

This video explains how to set up git hub to provide SSH capabilities from command line.

There were several videos available, but there was a code change and after going through several attempts, this vidoe has instructions that actually work.


https://www.youtube.com/watch?v=8X4u9sca3Io
this helped set up ssh keys and solved my confusion about the command line instructions


launch git bash terminal

in terminal

cd /d/github/Johnny_Data606

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

git status
git add .
git push git@github.com:yj07538/Johnny_Data606.git
