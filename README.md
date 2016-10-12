# TestGitAttributes

1. By default when core.autocrlf is true LF became CRLF
2. Using unset on text "-text" did not attempt to convert.
3. Changing the file pattern is OK
4. Change directory of the file doesn't need change in the pattern
5. removing "-text" make the file CRLF (exprected)
6. Try eol=lf
