### Split a string using awk

using `awk` to split `git-hub-pages` and echo `hub`

```bash
echo git-hub-pages | awk -F'-' '{ print $2 }'
```

