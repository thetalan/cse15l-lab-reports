[Ryan and Evans update code change](https://github.com/ryanyychen/markdown-parser/commit/2ae016f0b3aa46a36cc519ed4a31a528caddda06)
[Test file](https://github.com/ryanyychen/markdown-parser/commit/45129ad8c0007f3caf59e62eafab940095a18b97)

We made this change as this test file with the added new lines at the end of the file caused the code to not be able to find a new bracket or parentheses once it 
hit the first new line with no new files to read. This change was made to skip all new lines so it could reach the end of the file and stop the program if there were 
new lines after the last file.
