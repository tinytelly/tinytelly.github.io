### Split a string using awk

split **tinytelly.github.io** and output **github**

```bash
echo tinytelly.github.io | awk -F'-' '{ print $2 }'
```

