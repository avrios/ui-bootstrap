# Avrios Fork of angular-ui-bootstrap

## Fix process

* Make your changes and run `grunt build` (or `node_modules/grunt-cli/bin/grunt build` if you do not have it installed globally)
* Create a PR against `avr/develop`, and also the upstream if the fix could be useful to others
* Never rebase `avr/develop`, as then our `yarn.lock` on production may reference a commit that no longer exists
* Update the dependencies in our main app
