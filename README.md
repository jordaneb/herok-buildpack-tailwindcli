# heroku-buildpack-tailwindcli
This buildpack can be used to compile an app using the standalone Tailwind CSS (https://tailwindcss.com/) where an appropriate NodeJS runtime is not available or otherwise desired.

# REQUIRED CONFIGURATION

## `TAILWIND_OUTPUT_FILE`
**Example:** `static/style.css` - the output CSS file will be created at `/app/static/style.css`

The path, relative to the `/app` directory, that you need the CSS file to be created at.

# Support disclaimer
I made this buildpack for my own use on a private Dokku instance so consider this unsupported and if you would like to use it but need to change something to make it work for you then please fork the repo.
