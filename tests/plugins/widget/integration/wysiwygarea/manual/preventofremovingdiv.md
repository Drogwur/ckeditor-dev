@bender-ui: collapsed
@bender-tags: bug, 4.7.2, 704
@bender-ckeditor-plugins: image2, wysiwygarea, undo, sourcearea

----
1. Put caret in the text on the right and type some character.
1. Use `Ctrl + Z` or `Cmd + Z` shortcut to make undo.

**Expected:** Text returns to previous form. Below editor will be written `div` on green background.

**Unexpected:** Text moves below the image. Below editor will be written `figure` instead of `div`.
