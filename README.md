Binary encoded Database in C

Usage: ./bin/dbview -n -f <database file>

         -n - create new database file
         -f - required path to database file
         -a - add user to database
         -l - list database entries

Example:

         ./bin/dbview -f ./mynewdb.db -a "Timmy H.,123 Sheshire Ln.,120"

Run make to build

xdd <database file> to inspect entries
