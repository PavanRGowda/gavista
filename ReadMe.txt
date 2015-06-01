git init                                                           // Intiaties a local directory
git add filename						   // Adds it to staging stage (queued to commit stage)
git commit -m "Commit"						   // Queued file gets commited
git remote add origin https://github.com/PavanRGowda/gavista.git   // Creates a link between local and server repository
git push -u origin master					   // Pushes the file to github repository



git log								   // Maintains a log of commited history

sudo git show HEAD~2; test.php   (path)				   // Display the contents of file of particular commit

git log -n 1 -- test.php                                           // Latest commit log(Gives comment)

git diff HEAD^..HEAD						   // Displays latest commited file code

