Add text to a personal log.

Add the text directly

```sh
python /path/from/root/to/plog
Enter
multiline
text

```

(terminate with a double-newline).

Or with a pipe:

```sh
pbpaste | python /path/from/root/to/plog
```

Install by adding

```sh
export PATH="/path/from/root/to/plog/parent/dir:$PATH"
```

to `~/.bash_profile` (MacOS 10.12+).  Then you can run it from anywhere without including the path or invoking python directly:

```sh
plog
```

```sh
echo "test" | plog
```

