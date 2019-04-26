![cf](http://i.imgur.com/7v5ASc8.png) Lab 29: Routing and Component Composition
============================================================================

## Canvas Submission
[Lab Instruction](./LAB.md)
* **Code Sandbox Submissions**
* Please note that Assignments have not been brought in to the directories yet.
#### Assignment 1 - Warmups
[sandbox](https://codesandbox.io/s/p2kn5v56xj)  
[rendered stuff](https://p2kn5v56xj.codesandbox.io/)  

#### Assignment 2 - Modularize and Functionalize
* My initial Build modularized with classes
* Refactored for functions and classes to be included
[both](https://codesandbox.io/s/r4xx1o14yn)  
#### Assignment 3 - Conditionals
[sandbox for conditionals](https://codesandbox.io/s/wk2jy87jqk)
#### Assignment 4 - Modal
[Sandbox for modal](https://codesandbox.io/s/n30vrkzmj0)  
* modal is not completed
Testing
* as modules are not completed, testing is not completed


## UML OF Assignments 1-3
```
_____________           _____________  
|             |         |             |   
|  index.js   | =====>  |  index.html |  
|_____________|         |_____________|  
  
     /\  
    /||\                 part 2 adds in functional stuff  
     ||  
 _____________           _____________           _____________  
|             |         |             |         |             |   
|  index.js   | <=====  |  story.js   | <=====  |  detials.js |   FUNCTIONAL  
|_____________|         |_____________|         |_____________|  
 
     /\
    /||\
     ||         part 1 has stuff below                  part 3 adds this in
 _____________           _____________           ____________________
|             |         |             |         |                    | 
|  story2.js  |  <===== | details2.js | <=====  |  it/when/unless.js | 
|_____________|         |_____________|         |____________________|
   
   class based
   
   ```
    
### ASSIGNMENT 4 UML    
```
 _____________           _____________  
|             |         |             |   
|  index.js   | =====>  | index.html  |  
|_____________|         |_____________|  
  
     /\
    /||\
     ||
 _____________           _____________  
|             |        |             |   
|    app.js   |    <===| form.js     |
|_____________|        |_____________|        
  
     /\  
    /||\  
     ||  
 _____________       
|             |     
|  modal.js   |  
|_____________|      
```
    
    
