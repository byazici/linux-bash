## check result (0=success)
    echo $?

## send input to program
    prog < input

## running processes
    ps aux

## detail list
    ls -rtl

## Variables
    echo $PATH
    export PATH=$PATH:new_path
    /etc/environment

## popular devices
    /dev/random
    /dev/null/
    /dev/zero

## write output to file
    output > file-$(date).txt

## line count
    <out> | wc -l

## search x* named files
    find . -name x*

## json parse
    curl url | jq -r *.[0].Address

## device forward
    dd if=/dev/zero of=zero-file.txt bs=512

## show non printable files
    hexdump file

## reset screen
    reset

## monitoring
  iostat
  top


