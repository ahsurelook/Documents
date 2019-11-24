# Powershell Commands

# Move all files out of loads of folders at once
Get-ChildItem -Path source -Recurse -File | Move-Item -Destination dest
(source=.     dest=. ) -> this will take everyfile sub folder in folder X and put all files into folder X


