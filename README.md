`plog`: Personal log
====================

Add text to a personal log.

When run, the input text will be added to a file named `YYYY-MM-DD.txt` with a `hh:mm` timestamp.


Ways to invoke
--------------

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


Configuration
-------------

Target path set in the script itself.


Installation
------------

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
