## To get started

Clone the repository, then run 'bundle install' and 'npm install' to get dependencies.

To run the app, you can run either 'npm run start', or 'bundle exec jekyll serve'

If you want to edit the sass in the _USWDS folder and have it update live, use 'npm run watch-start'

## USWDS setup

Sass based on the USWDS system sound be added to the _uswds-theme-custom-styles.scss file.

All other sass can be added into the jekyll _sass file, and the file name added to the entry point in assets/css/style.scss

Edits made to _sass/styles.css will not be retained when the site is built.  It is overwritten when the USWDS scss is compiled.

USWDS location settings are in the gulpfile

## Collections

Collections are now stored in sn_collections and sorted by type

If an additional category is needed, a new folder should be made and its information should be added to the _config.yml under 'collections'
