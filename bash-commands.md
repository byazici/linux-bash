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

## see hosts file
  cat /etc/hosts

## list processes sarts with postgres
ps auxww | grep ^postgres

## manage jobs

### view jobs
jobs

### run jon in bg
cp xyz *&*

### Moving a foreground job to the background and stop
^Z

### resume bg process
bg %1

### Moving a background job to the foreground
fg %1

### Terminating job
kill %1
