# Day-One-SC
1 - $ ssh-keygen -t ed25519 -C "alii.muhammad9399.com" 
    To Create an SSH Key and Add it to GitHub
2 - $ ssh-add ~/.ssh/id_ed25519
    To Add the SSH private key
3 - $ cat ~/.ssh/id_ed25519.pub
    To Copy the SSH public key
    And Add the SSH key to GitHub
4 - $ git init Day-One-SC
    To Create a new local repository
5 - $ cd Day-One-SC
    To navigate to the desired folder and run
6- $ echo "Ali" > index.html
    To Create a file named index.html
7 - $ git remote add origin git@github.com:AlyMuhammad2/Day-One-SC.git
    To Add the remote repository
8 - $ git add index.html         ---> Stage
    $ git commit -m "index file" ---> commit
    $ git push -u origin master    ---> Push 
