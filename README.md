# Overview

This is the .gitignore file I use for WordPress repositories. It has worked well so far for sites that have a custom theme but manage plugins through the usual WP built-in update mechanisms.

# Plugins

All plugins are ignored.

# Themes

Only the base WordPress themes are ignored. Themes with a built-in update mechanism may end up tracked here, which could cause complications.

# Cruft, WPEngine, etc.

Rules are included to ignore cruft added by operating systems, IDEs, utilities, and loggers, as well as filetypes that WPEngine doesn't support when pushing to their remotes.