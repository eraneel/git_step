# git_step
git installtion step in RHEL 8
code
<br>

sudo dnf update -y        # update your local package 

sudo dnf install git -y   # install git

git --version             # check version

--------------------------------------------------------

Setting Up Git

code 
<br>
git config --global user.name "Your Name"   # git user name

git config --global user.email "youremail@domain.com" # git mail_id

git config --list  # display all of the configuration items that have been set by typing:

Output
user.name=Your Name
user.email=youremail@domain.com
..
# or

vi ~/.gitconfig  # The information you enter is stored in your Git configuration file, which you can optionally edit by hand with a text editor like this 

~/.gitconfig contents

[user]
  name = Your Name
  email = youremail@domain.com



Press ESC then :q to exit the text editor.
