## About

This is my personal vimrc that anyone can get it.

## Quick start

1. Get it:

     ```
     git clone https://github.com/douglarek/.vim.git .myvim
     ```
     It takes `vim vundle` with `git submodule`, if you want to use it:

     ```
     git submodule init
     git submodule update
     ```
     Or, maybe you would love to do it all by one step:
     ```
     git clone https://github.com/douglarek/.vim.git .myvim --recursive
     ```

2. Configure it:

    ```
    ln -s .myvim/.vim .vim
    ln -s .myvim/.vimrc .vimrc
    ```
    before this, please backup your own data, then install bundles:
    ```
    vim +BundleInstall +qall
    ```

3. Update it:

    ```
    cd .myvim
    git pull
    ```
