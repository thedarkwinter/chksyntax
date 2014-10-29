### chksyntax

Recursive syntax checker for multiple scripts / languages

* * *


Currently Supports: bash, php, perl, python, ruby
    - going to add more in the future

#### Usage
``` shell
Usage: chksyntax [arguments] [files|paths]
  -h this help
  -r recursive
  -v verbose, output even when passed
  -i ignore unknown files
```

You can also put a file called .chksyntax in your home directory or a project directory containing default configuration

##### Valid options
``` shell
scripts=( bash php )    - Only check these scripts
paths=( path1 path2 )   - For a project directory where you only want to check particular sub directories
maxdepth=10             - The depth for recursion where 1 is not recursive
ignore=1                - ignore unknown script types
verbose=1               - be verbose
```
