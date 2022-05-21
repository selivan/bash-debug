A simple debugger for bash.

Each script command is printed before execution. Then command prompt appears (no autocompletion). Prompt includes the last command return value. You can print a command to execute or an empty line to continue.

Note: `set -T` is used, changing DEBUG and RETURN traps inheritance.
