> 📘 This note is part of my personal learning journal while reading *Software Engineering for Data Scientists*.
> Some sentences are quoted directly from the book for educational purposes only.  
> All rights belong to the original author and publisher.


## Key point:

### 1. Basic: 
 Read error message
   
### 2. Handling errors in the code
Best Practice :
   ```
   try:
      xxx
   except KeyError:
      yyy
   else:
      zzz
   ```

never :
    
   ```
   except:
    return
   ```

   It silences all the errors it encounters


### 3. Logging

Setting the level of logging

  ```
  import logging

  loggin.basicConfig(level= logging.DEBUG)
  ```

How to log

  ```
  from scipy.stats import linregress

  def qqq_trend(year, data):
      logging.info("Running the qqq function")
      # then can put the "try: / except TypeErrors as e: / else" structure
  ```

### 4. Debugging

1. use log above
2. 2.add flag in code


---
tags: [personal-note, SE4DS, learning, non-commercial]
