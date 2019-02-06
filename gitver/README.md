Git Version (version 1.0)
=========================

URL: https://github.com/charlesbaynham/gitver
(c) Charles Baynham 2019

License: LaTeX Project Public License 1.3c

This package will get a description of the current git version of this
document and store it in a command `\gitVer`. If memoir or fancyhdr are in use, it
will also add this to the document footers unless the option "noheader" is
passed.

It also defines a command `\versionBox{}` which outputs a box containing the
version and date of compilation

For this to work, you must have git installed and available on the command
line, this document must be part of a git repository, and latex must be
running in "shell escape" mode. This can be enabled by passing `--shell-escape`
on the command line when compiling your docuemnt, or will be available in the
options of whatever GUI you're using (try Googling).

Note that it's a good idea to tell git to ignore all the latex auxilary files,
otherwise your version will always be "dirty". Try the `.gitignore` file from
[gitignore.io](https://www.gitignore.io/api/latex) if you don't already have
one.

The package is released 'as is' with no warranty under the LaTeX Project Public
License, version 1.3c.
