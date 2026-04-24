You should now have the mkdocs command installed on your system. Run mkdocs
--version to check that everything worked okay.

$ mkdocs --version
mkdocs, version 1.2.0 from /usr/local/lib/python3.8/site-packages/mkdocs (Python 3.8)
Note

If you would like manpages installed for MkDocs, the click-man tool can generate and install them for you. Simply run the following two commands:

pip install click-man
click-man --target path/to/man/pages mkdocs
See the click-man documentation for an explanation of why manpages are not automatically generated and installed by pip.

