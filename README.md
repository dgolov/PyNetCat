# Py Netcat

## Ho to use?

Help mode:

```bigquery
python python netcat.py -h
```

### Client example

```bigquery
python python netcat.py -t 0.0.0.0 -p 5555 -l -c
```

### Server example

```bigquery
python python netcat.py -t 0.0.0.0 -p 5555
```

Now press **Ctrl+d** to enter command mode

```
BHP: #> 
> la -la
total 32
drwxr-xr-x   8 dgolov  staff   256 Dec 21 21:40 .
drwxr-xr-x  18 dgolov  staff   576 Dec 14 17:45 ..
drwxr-xr-x  13 dgolov  staff   416 Dec 21 21:37 .git
-rw-r--r--   1 dgolov  staff    32 Dec 21 21:19 .gitignore
drwxr-xr-x   9 dgolov  staff   288 Dec 21 21:39 .idea
-rw-r--r--   1 dgolov  staff   265 Dec 21 21:40 README.md
drwxr-xr-x   6 dgolov  staff   192 Dec  5 22:38 env
-rw-r--r--   1 dgolov  staff  4141 Dec 21 21:35 netcat.py
```