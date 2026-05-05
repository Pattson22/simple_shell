0x16. C - Simple Shell


# simple_shell

**One-line summary:** Minimal Unix shell implementation to practice parsing, process control, and builtins.

## Overview
A small shell that supports command execution, basic builtins, and simple piping. Designed to demonstrate understanding of process creation, exec family, and I/O redirection.

## Key features
- Command parsing and tokenization
- Builtin commands: cd, exit
- Support for simple redirection and pipelines

## How to build and run
```bash
git clone git@github.com:Pattson22/simple_shell.git
cd simple_shell
make
./simple_shell


Examples

$ ./simple_shell
$ ls -la | grep txt > out.txt
$ cd /tmp
$ exit


Design notes
Simple lexer and parser for command lines

Focus on robust error handling and resource cleanup

Tests and CI
CI runs make and make test where available. See .github/workflows/ci.yml.

What I learned
Process control and inter-process communication

Shell design tradeoffs

License
MIT
