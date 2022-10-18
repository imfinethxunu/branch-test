# Lecture Note_5
- - -
### OUPUT
- Standard output is screen
-> using ">" after a command
- Existing file
-> using ">>"

### INPUT
- standard output is from keybord
-> using "<"

#### Pipelines "|"
- output of previous command to input of next command.
-> ex) command1 | command2 | command3

#### Permissions
- Linux is a multi-user system
file type/ owner / group / other
-> ex) -rwx rwx rwx

#### Changing Permissions
- "chomod" -> change permissions
ex) chomod 600 some_file
6 = 100 = rw- owner
0 = 000 = --- group
0 = 000 = --- group

#### Superuser
- has all system administation authority

### Shell Script
- Write and Run a shell script

##### Tip : history
- Type "history" 
--> to see previous command history 
--> or save it to a text file