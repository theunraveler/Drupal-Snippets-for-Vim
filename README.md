I'm beginning to see the light: Vim is awesome.

However, there is nothing for Vim that matches the PHP Drupal bundle for Textmate, what with the autocompletion and snippet goodness. So here will be an ongoing attempt to recreate that in Vim using the snipMate plugin.

## Configuration

These snippets require the [snipMate](http://www.vim.org/scripts/script.php?script_id=2540) plugin for Vim. 

Once you get that up and running, just checkout as a 'drupal' directory
in your ~/.vim/snippets (or wherever you install your Vim scripts to),
like so:

     cd ~/.vim/snippets # You may have to create it, first.
     git clone git clone https://github.com/berkes/Drupal-Snippets-for-Vim # checkout

For the snippets to work, the filetype needs to specify `drupal`.

You may want to use the [Drupal Plugin for Vim](drupal.org/project/vimrc) which will do this for you, or, in your `.vimrc` file, add the line:

  :set filetype=drupal.php
