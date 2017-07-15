### Split a string using awk

awk to split `git-hub-pages` and output `hub`

```bash
echo git-hub-pages | awk -F'-' '{ print $2 }'
```

