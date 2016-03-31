Git configuration problem

*****error: could not lock config file .git/config: No such file or directory*****


Check if you have a .git directory in your home folder and if you don't:

mkdir ~/.git

Then
$git config user.name "username"
$git config user.email "email@email.com"

*****end***************


