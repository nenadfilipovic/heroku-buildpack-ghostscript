# Heroku Buildpack: Ghostscript

Installs Ghostscript on Heroku platform.

## Install

    # Add buildpack to your instance.
    - Via website: nenadfilipovic/heroku-buildpack-ghostscript
    - Via cli: heroku buildpacks:add nenadfilipovic/heroku-buildpack-ghostscript

    # Push changes to deploy.
    $ git push

    # This version of ghostscript will end up deployed at /app/vendor/ghostscript/bin/gs
