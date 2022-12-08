#!/bin/bash
gcc -E $CFILE -o c
gcc -c $CFILE
gcc -S $CFILE -o "{$CFILE}.s"
gcc $CFILE -o cisfun
