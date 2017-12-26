# Find IP in files

```
grep -oh '[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}\.[0-9]\{1,3\}' *.txt

-h, --no-filename
    Suppress the prefixing of file names on output. This is the default
    when there is only  one  file  (or only standard input) to search.
-o, --only-matching
    Print  only  the matched (non-empty) parts of a matching line,
    with each such part on a separate output line.
    
```


# Find keyword/word in files

Ack is designed as a replacement for 99% of the uses of grep.

```
ack 'word'
```
