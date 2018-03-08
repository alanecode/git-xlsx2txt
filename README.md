# git-xlsx2txt
Simple wrapper script calling the python CLI [`xlsx2csv`](https://github.com/dilshod/xlsx2csv) to convert all sheets in a provided .xlsx file to csv format. 

Then, by setting up a diff filter in [`.gitattributes`](https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes#Binary-Files) and specifying this wrapper in [`.gitconfig`](https://stackoverflow.com/questions/17083502/how-to-perform-better-document-version-control-on-excel-files-and-sql-schema-fil) we can have git diff compare versions of the input spreadsheet /after they have been passed through the filter/.
