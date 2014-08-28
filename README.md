git-hooks
=========

Hooks for git

Includes:

* self-updating hooks

* spelling check for commit messages
* checks for cpp google style
* checks for pdb
* checks for pep8
* checks for tabs
* checks for end of line spaces
* checks for beautiful xml files


Usage
=====

To use, simply copy the standard git-commits to the hooks folder and
then add utils/git-hooks (this repo) to the top level of your
repository.

    cd your_repo
    mkdir utils
    git submodule git@github.com:brianbruggeman/git-hooks.git utils/git-hooks
    cp utils/git-hooks/pre-commit .git/hooks/
    cp utils/git-hooks/commit-msg .git/hooks/

Enjoy!