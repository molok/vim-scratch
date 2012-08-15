Scratch
=======

You can use the scratch plugin to create a temporary scratch buffer to store
and edit text that will be discarded when you quit/exit vim. The contents
of the scratch buffer are not saved/stored in a file.

Installation
------------
1. Copy the scratch.vim plugin to the $HOME/.vim/plugin directory. Refer to
   the following Vim help topics for more information about Vim plugins:

      :help add-plugin
      :help add-global-plugin
      :help runtimepath

2. Restart Vim.

Usage
-----
You can use the following command to open/edit the scratch buffer:

      :Scratch

To open the scratch buffer in a new split window, use the following command:

      :Sscratch

You can toggle the Scratch window using

      :ScratchToggle

Similar command using vertical split instead of horizontal are available:

      :Vscratch
      :VscratchToggle

When you close the scratch buffer window, the buffer will retain the
contents. You can again edit the scratch buffer by openeing it using one of
the above commands. There is no need to save the scatch buffer.

When you quit/exit Vim, the contents of the scratch buffer will be lost.
You will not be prompted to save the contents of the modified scratch
buffer.

You can have only one scratch buffer open in a single Vim instance. If the
current buffer has unsaved modifications, then the scratch buffer will be
opened in a new window

