# Some build issues

- -Werror
disable it in makefile

- execv(executable_path=.., ...) failed in maxvm: no such file or directory
set environment variable DYLD_LIBRARY_PATH to the directory of libjvm.dylib
