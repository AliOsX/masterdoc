# Repo of repos!
The master branch of this repo is unimportant. The important branch is `gh-pages`, used to serve the Next Thing Co documentation at [docs.getchip.com](http://docs.getchip.com).

This `gh-pages` branch is the result of a remote script that monitors the repositories in the [getchip organization](http://github.com/getchip) and:

 * detects changes in any of the repositories in this organization
 * renders the static HTML pages for documentation
 * changes the name of the index pages for each product
 * merges the unique content from the individual repos into this repo's `gh-pages` branch
