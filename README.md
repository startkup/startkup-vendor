TKUAIIC-Vendor
================

git submodules shared in or out for use with [TKUAIIC].
This repository is maintained for use on the Tamkang University Artificial
Innovative Intelligence Club affairs, but may be partly opened for anyone
wishing avoid have to directly ask for open data from TKUAIIC.


File Structure
-----

Files should be in a `/<provider>/<repository>` structure in this repository.


Usage
-----

Checkout this git repository into `/vendor` using `git clone <URL>` or add the
repository as a git submodule using `git submodule add <URL> vendor` followed
by `git submodule update --init`.


Adding or updating git submodules
----------------------------

0. Read the [documentation] on the process for adding new submodules.
1. In some cases, the submodules might include not needed files (e.g. test files,
   project files, etc). If you cannot exclude them from submodules's archive
   (e.g. by `export-ignore`ing unwanted files in submodules's `.gitattributes`
   file), you can skip checking them in by listing them in `.gitignore` file.
2. Add and commit changes as a git patch.
3. Review and merge changes.

If in doubt, seek advice from regular commiters to this repository.


[TKUAIIC]: https://github.com/tkuaiic/tkuaiic
[documentation]: https://www.mediawiki.org/wiki/Manual:External_libraries