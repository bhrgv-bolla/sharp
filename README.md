SHARPE: REPLENISH ME
---------------------

1. USE git to download the files to a local repository 
   
    Here are commands on how to do that:
      
      1. mkdir <project-folder-name>;
      2. cd <project-folder-name>;
      3. git init;
      4. git remote add origin git@bitbucket.org:sharp_app/sharp.git;
      5. git pull origin master.

In case, you face any issues with committing the code. You should probably authenticate the PC you are working from by adding your SSH key to your bitbucket account.

2. Commit changes:
     
      1. git commit <file-path> -m <commit-message>
      2. git push -u origin master


SOME_HELP
-------------------------
http://stackoverflow.com/questions/1783405/checkout-remote-git-branch
http://stackoverflow.com/questions/5601931/best-and-safest-way-to-merge-a-git-branch-into-master