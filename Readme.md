# ORG html themes</font>

This is a forked repository of the org-html-themes created by Fabrice Niessen.

## Using a theme

Using a theme from the theme gallery for your own Org documents is very easy:

You add a #+SETUPFILE: directive in the preamble of your document (to include the necessary CSS and JavaScript files).
You can either use an URL of the following type for the “setup file” of your chosen theme:

```
#+SETUPFILE: https://fniessen.github.io/org-html-themes/org/theme-NAME.setup
```

(where NAME is either bigblow or readtheorg)

or, if you cloned or downloaded the Org-HTML themes project – to get no dependency on an Internet connection –, use a (relative or absolute) path to the local “setup file” and copy the src folder from the cloned folder into the same folder as the file you want to export:

```
#+SETUPFILE: PATH/TO/GIT/REPO/org/theme-NAME-local.setup
```
 
Then, you export your Org mode file to HTML with org-html-export-to-html or with C-c C-e h h.