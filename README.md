# Pybites Search

A command line tool to easily search across Pybites content.

## Installation

```
$ pip install pybites-search
```

## How to run it:

```
$ search --help

 Usage: search [OPTIONS] COMMAND [ARGS]...

╭─ Options ───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.                                                                                     │
│ --show-completion             Show completion for the current shell, to copy it or customize the installation.                                              │
│ --help                        Show this message and exit.                                                                                                   │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│ article                                                                                                                                                     │
│ video                                                                                                                                                       │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯

$ search article zipfiles
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃ Title                                        ┃ Url                                   ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│ How to Create and Serve Zipfiles from Django │ https://pybit.es/django-zipfiles.html │
└──────────────────────────────────────────────┴───────────────────────────────────────┘

$ search video property
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃ Title                                ┃ Url                                         ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│ Python @property decorator explained │ https://www.youtube.com/watch?v=8BbngXWouzo │
└──────────────────────────────────────┴─────────────────────────────────────────────┘
```
