followed this tut:
https://github.blog/2016-02-01-working-with-submodules/

1. from terminal, go to were .vscode is / root of the repository.
2. git rm -r .vscode
3. git commit -m "remove vscode(for sub module)"
4. git submodule add https://github.com/ricardosantos79/vscode_pinescript_snippet .vscode
5. git commit -m ".vscode submodule"
6. git submodule update --init --recursive

and should be set now, gona do a update test to see if its working