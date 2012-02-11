# makeport
A port helper script for quick port templating.

## Features
- Create port files from a URL
	- auto parse version from url.

- Simple REPL for easy patching of files
	- auto backup file to edit.
	- opens file in $EDITOR
	- removes the need to cd $( make show=WRKSRC )
	- keeps error messages from _make build_ for quick reference
