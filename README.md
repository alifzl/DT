# DT (Directory Tree)

DT is a command-line tool to generate a directory tree diagram.

```sh
$ python dt.py /path/to/directory/
```

**Note:** The `-h` or `--help` option provides help on how to use RP Tree.

To take a quick test on **DT**, you can use the sample `home/` directory provided along with the application's code and run the following command:

```sh
(venv) $ python dt.py ../hello/
../hello/
│
├── hello/
│   ├── __init__.py
│   └── hello.py
│
├── tests/
│   └── test_hello.py
│
├── requirements.txt
├── setup.py
├── README.md
└── LICENSE
```

That's it! You've generated a nice directory tree diagram.

## Current Features

If you run DT with a directory path as an argument, then you get the full directory tree printed on your screen. The default input directory is your current directory.

DT also provides the following options:

- `-v`, `--version` shows the application version and exits
- `-h`, `--help` shows a usage message
- `-d`, `--dir-only` generates a directory-only tree
- `-o`, `--output-file` generates a tree and save it to a file in markdown format
