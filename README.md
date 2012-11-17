glsl.vim
========

OpenGL syntax highlighter for C and C++ source files.

Instructions
-----------------------------------------------------------

Using the Pathogen plugin:
(http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)

From your ~/.vim directory:
    git submodule add git://github.com/beyondmarc/opengl.vim.git bundle/syntax_opengl

If not using the Pathogen plugin:
Add the opengl.vim file into your vim syntax folder (in most Linux distros:
/usr/share/vim/vim\<version\>/syntax), and add the following line at the bottom
of your .vimrc file (for vim 7.2+):
    
    autocmd FileType c,cpp,h,hpp source /usr/share/vim/vim72/syntax/opengl.vim

