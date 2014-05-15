agl
---

List files *and directories* using
[ag](https://github.com/ggreer/the_silver_searcher).

### Why?

`ag -g ""` is useful for listing the files under the current directory as it
respects .gitignores and stuff, but directories are not included. agl is a very
simple wrapper script around the command that prints the names of the
directories as well.

