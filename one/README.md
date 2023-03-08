Description:
---

AirBnB is a web app with a full development of back-end and front-end API integrating also SQL storage.

Console:
---

The console is a CLI that allows the use of data as backend tool. It can be used to handle all classes predefined previously called into storage object

How to use:
---

```
In interactive mode
-----

$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
(hbnb)
(hbnb) quit
$
```

```
In non-interactive mode
-----

$ echo "help" | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```


How to Test:
---

Unittests for the CLI AirBnB project are defined in the tests folder. Execute the following command to run the entire test suite simultaneously:
$ python3 unittest -m discover tests You can also specify a single test file to run at a time:
$ python3 unittest -m tests/test_console.py

**Author:** Ahamefula Chibundu <https://github.com/chibunduuchechi>
