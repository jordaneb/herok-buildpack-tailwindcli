# heroku-buildpack-tailwindcli
This buildpack can be used to compile an app using Tailwind CSS (https://tailwindcss.com/) where a NodeJS runtime is not already available.

# Configuration
It is necessary to set the `TAILWIND_OUTPUT_FILE` environment variable to tell Tailwind CLI where to output the CSS bundle relative to the app root directory. For example: `TAILWIND_OUTPUT_FILE=static/style.css`.

# Disclaimer
I made this buildpack for my own use on a private Dokku instance so consider this unsupported and if you would like to use it or need to change something to make it work for you then you should fork the repo.

Many thanks
