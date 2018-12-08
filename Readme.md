# Comment travailler avec VScode.
# Uninstall visual studio code in windows
```
Open Run (Win + R)
Enter %appdata%
Press Enter
Delete the folder Code.
```
Voila! Restart Visual Studio Code and it is reset!


…or create a new repository on the command line
echo "# vscode" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/guirre/vscode.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/guirre/vscode.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


