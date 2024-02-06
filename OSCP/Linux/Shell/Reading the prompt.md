
What is the prompt?
````<username>@<hostname><current working directory>$
````





```
##Unprivelaged user
$ 

##Root
#
```


## File descriptors

- =filehandle in windows
- Used to perform Input/output by kernel

### Three types
- `STDIN - 0`  / *data stream for input*
	- Input into CLI 
- `STDOUT -1` / *data stream for output*
	- Successful results of input printed in cli (green)
- `STDERR -2` / *data stream for output of error*
	- Errors printed in cli (red)
![[Pasted image 20240128182125.png]]

## Basic Redirects 
- `<` = from where (often implied, i.e invisible and not nesscary) eg. `cat test.txt` is the same as `cat < test.txt`
	- read `cat` from `text.txt`
- `>` = where to
	- eg. `ls > list.txt`
	- read `ls` into the file `list.txt`

## Redirect Pipes
- `|` alternate to `>` to redirect STDOUT




 - `EOF` aka End-Of-File linux function