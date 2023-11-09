A simple debugger for bash.

Each script command is printed before execution. Then command prompt appears (no autocompletion). Prompt includes the last command return value. You can print a command to execute in the script context or an empty line to continue.

```bash
bash-debug script-to-debug.sh [script args]
```

Note: `set -o functrace` is used, changing DEBUG and RETURN traps inheritance for shell functions.
