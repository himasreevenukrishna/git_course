<h1>Revert changes on git</h1>
<h2>Revert changes from working directory</h2>
git restore <file_name>
or
git checkout ---<file_name>
Note: even you can remove charges manually. But if we have updated multiple files and don't know which lines to remove this command really helps.
<h3>Revert changes from staging area</h3>
git restore --staged <file_name> #to revert changes from staging area to working directory
git restore <file_name> #to revert from working directory.
<h4> Revert changes from Local Repository </h4>
git reset HEAD^  #to revert changes from local repo to working directory
git restore <file_name(s)> #to revert changes from working directory

<h5>Revert changes from Remote Repository </h5>
we don't have direct way to do this
