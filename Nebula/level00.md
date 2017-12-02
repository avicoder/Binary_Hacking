## Level 00

 - Something to do with SUID
 - Sticky but is set means user can execute/read/write as root, depending on where the sbit is placed.
 - Found Sticky bit set for flag00 user `find / -perm +4000 -user level00 -type f -print`
 - Found `-rwsr-x--- 1 flag00 level00 7.2K 2011-11-20 21:22 /bin/.../flag00`
 
 
         level00@nebula:~$ /bin/.../flag00
         Congrats, now run getflag to get your flag!
         flag00@nebula:~$ getflag
         You have successfully executed getflag on a target account
         flag00@nebula:~$
 
  - Done
