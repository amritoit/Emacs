git pull https://github.com/amritoit/Emacs.git

branch final

make 
sh install.sh

cd amrit-config
cp .emacs ~/.emacs
cp .emacs.d ~/.emacs.d
cp .bashrc ~/.bashrc

then run "emacs -daemon""
you can check the error with "emacs --debug-init""
