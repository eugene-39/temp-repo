### Git bash
---
## Standard output 

## Standard output 
스크린이 아닌 어떠한 다른 것으로 바꾸어줄 수 있다  
This can be changed to anything other than a screenshot.


1. cat : Copy the contents in some text file.
```sh
$ cat.file_list.txt
```

2. Pipeline 
 - It takes the previous output as it is into the input.
 - command1|command2|command3
```sh
$ ls -lh | less (press "q" key to exit the screen.)
```

```sh
$ echo ~
$ echo print out the text 


$ ls -1
```

### Permissions(권한) 
Linux <= Multi user system 
-rwxrwxrwx 
-Connect each individual's computer to the server, connect the files on the server or the resources of the system
-On Linux, files and directories are divided into three levels.
-It is important that divides directory or not. 

"chmod" changes permissions. 

777 : No restrictions on permissions. Anybody may do anything. Generally ot a desirable setting.  
755 : (rwxr-xr-x) The file's owner may read, write, and execute the file. Nobody else has any rights. This setting is useful for programs that only the owner may use and must be kept private from others.  
644 : (rw-r--r--) The owner may read and write a file, while all others may only read the file. A common setting for data files that everybody may read, but only the owner may change.   
666 : (rw-rw-rw-) All users may read and write the file.   


## Superuser 
- A superuser has all system adimnistation aythority.  
- Some commands needs superuser's privilleges.   
- Put "Sudo" before the command if you are a superuser. 

- Type "exit" to get out of a superuser session.

  In Linux, you can choose CLI - based or GUI-based text editors.


  vi, vim /Emaxs/nano/gedit/kwrite
