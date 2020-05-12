# Replacing SQLite with Cell, parts 1-2

This is the companion repository for the first two posts in the *Replacing SQLite with Cell* series:

* <a href='https://medium.com/@cell.lang.dev/replacing-sqlite-with-cell-part-1-fb5d636b5fd0'>Replacing SQLite with Cell, part 1: Meet the programmable database</a>
* <a href='https://medium.com/@cell.lang.dev/replacing-sqlite-with-cell-part-2-a5eb6a21de2d'>Replacing SQLite with Cell, part 2: Complex queries and custom types</a>

This is the cross-platform version. You can find the Windows-only one <a href='https://github.com/cell-lang/replacing-sqlite-with-cell-part-1-2-windows'>here</a>.

You'll need to install the .NET Core SDK 3.1 or later first. Once you've done that, just cd into the repository's directory and type *make*. Then follow the on-screen instructions.

There are two versions of this project. The one that is built by default is written entirely in Cell. The other one is a mixed language application, where the classes generated by the Cell compiler are used in hand-written C# code. Their output is almost identical. To build the embedded version type *make embedded*.

The recommended editor for browsing and editing Cell code is Sublime Text 3. You can find the syntax highlighting files in ```compiler/sublime-text/```. Just copy them in ```~/.config/sublime-text-3/Packages/User/```.