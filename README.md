# QCheck
Checks files for changes and if they got deleted.

## How To
- Start it with 2 arguments: [--create, --check, --createtree or --checktree] and [path]
- Example: QCheck.exe --create C:\Users\Test\Downloads\

### Create
--create creates an index file called checks.md5. Do this first.

### Check
--check reads the index file and reports wich files changed.

### Create Tree
--createtree creates an index file called checks.tree which contains a list of files. Use this first if you want to check if files disappeared.

### Check Tree
--Checktree reads the index file and reports which files don't exist anymore.
