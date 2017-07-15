### <a name="split-a-string-using-awk">Split a string using awk</a>

split **tinytelly.github.io** and output **github**

```bash
echo tinytelly.github.io | awk -F'-' '{ print $2 }'
```
---
### Bash to find a word contained in a string

evaluate **branch** called **scratch-branch** contains the string **scratch**

```bash
if [[ $branch == *scratch* ]]
then
   echo "$branch contains scratch"
fi
```


