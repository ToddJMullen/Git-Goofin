Lines from the CLI for README

I just added these lines.

This is another time around that I'm adding some stuff to be commited.

I just added / staged and commited this at once using:
	git commit -a -m "commit msg here..."

I'm adding this message in the middle here because I just re-read this and need to note that the above comman (git commit -a -m "yada yada...") will not "add/stage" *NEW* files.  They have to be "git add"ed to the index. git commit -a -m "..." will stage and commit modified files that are already being tracked.

Then I undid the commit so that I could modify it (however) and then re-commit it using:
	git reset --soft HEAD^
...and that's when I added thses last few lines to be included.

This line was added remotely by the other guy in order to create a con flict in the second remote commit that will arise during the rebase that will be perfomed when the remote differs and I don't want to merge.
