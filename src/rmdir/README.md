## rmdir

Usage: rmdir [OPTION]... DIRECTORY...        
Remove the DIRECTORY(ies), if they are empty.
  -I, --ignore-fail-on-non-empty
                  ignore each failure that is solely because a directory
                  is non-empty
  -p, --parents   remove DIRECTORY and its ancestors; e.g., 'rmdir -p a/b/c' is
                  similar to 'rmdir a/b/c a/b a'
  -V, --verbose   output a diagnostic for every directory processed
  -h, --help      display this help and exit
  -v, --version   output version information and exit