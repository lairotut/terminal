# Some tricks

## Find the full path you are

```bash
echo $(cd $(dirname "$1") && pwd -P)/$(basename "$1")
``` 
