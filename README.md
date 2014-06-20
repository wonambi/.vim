https://github.com/tpope/vim-pathogen
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim


git submodule init
git submodule add git://github.com/tpope/vim-fugitive.git bundle/vim-fugitive
git commit -m 'Added vim-fugitive'
git push origin master

git submodule add git://github.com/klen/python-mode.git bundle/python-mode
git commit -m 'Added python-mode'
git push origin master

