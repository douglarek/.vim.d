## About

*NOTE* this repo is **Deprecated**.

This is my personal vimrc that anyone can get it.

## Quick start

1. Get it:

     ```
     git clone https://github.com/douglarek/.vim.d.git .vim.d
     ```
     It takes `vim vundle` with `git submodule`, if you want to use it:

     ```
     git submodule init
     git submodule update
     ```
     Or, maybe you would love to do it all by one step:
     ```
     git clone https://github.com/douglarek/.vim.git .vim.d --recursive
     ```

2. Configure it:

    ```
    cd
    ln -s .vim.d/.vim .vim
    ln -s .vim.d/.vimrc .vimrc
    ```
    before this, please backup your own data, then install bundles:
    ```
    vim +BundleInstall +qall
    ```

3. Update it:

    ```
    cd .vim.d
    git pull
    ```
