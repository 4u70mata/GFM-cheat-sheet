# Introduction to GitHub Flavored Markdown (GFM):  
  

Github Flavored Markdown (GFM) is a popularly used markup language among github users to creat richly formatted content. It was built upon the standard [Mardown](https://fr.wikipedia.org/wiki/Markdown "See wiki for more") syntax introduced in 2004 by John Gruber with the help of Aaron Swartz. Of course with some additional features 
proper to Github.

## Some Key features: 
First before introducing some general features , GFM support Unicode characters, also ASCII punctuation characters like !, ", #, $, %, &, ', (, ), *, +, ,, -, ... and much more 

__New line:__ To start a new line simply end the line with two consecutive spaces ' . . ' .  
__Code:__ Code cells like these can done using :  
+ -> tabulation : for example ->bim->bam->->bam.   
    (remember to endent after the + )     

        bim
        bim
            bam        
    
    Or using this synthax along with language(optional):  
    (without indentation, also use a Backticks :(`) not the single quote ('))
    
    ```Python
        '''
        GFM way to display code (python in this case)
        ```Python 
        
        ```  
        '''
        def function1():
            pass  

    ```
__Horizontal Rules:__ 
        
    ...___  3spaces along with 3 _ 
    can be performed also with * and - but strictly above 1 space...
       ***
       ___
       ---
       <hr/>
    Also one, two or three doesn't give the same result
    .*** 
    ..***
    ...***
   ***
   ___
   ---
   <hr/>
The following rule (hr) doesn't simply follow the indentation.(required after the + Horizontal Rules: )    

-  first level
    - second level
        <hr/>   

__Inline code span :__ `i++` or `*` , in other words a piece of code to display within paragraph.

        `i++` to emphasize the fact that i++ is a special code (also for *)
  

  
## Features :
### **Headers** :  
GFM supports headers similarto standard Markdown.  
```Markdown 
    # Header 1 (big header used)
    ## Header 2 
    ...
    ###### Header 6 (smallest header)
```

### **Emphasis:**

Emphasize text using asterisks symbol `*`, underscores `_` for italic and double asterisks `**` or `__` for bold also ~~strikethrough~~ .

```markdown
*italic* or _italic_
**bold** or __bold__
Combination is also possible:
**_bold and italic_**
~~strikethrough~~ 
```

### **Lists:** 
Like HTMl GFM support also ordered and unordered lists, also list nesting to create sub-lists.

Unordered List:  

- Item 1
- Item 2
  - Sub-item 1
    - Sub-sub-item 1
        - Sub-sub-sub-.
            - Subsss...
  - Sub-item 2

```
- Item 1
- Item 2
  - Sub-item 1
    - Sub-sub 
        - And so on sbsbsbsss ...
  - Sub-item 2
```

Ordered List:  

1. Item 1
2. Item 2
   1. Sub-item 1
        1.  Sub-sub-item 1
   2. Sub-item 2

```
1. Item 1
2. Item 2
   1. Sub-item 1
        1.  Sub-sub-item 1
   2. Sub-item 2
```

### **Links:** 

Possibility of including links with inline `[Link Text](URL)` syntax for example.

  - inline links :  
        Click [here](https://www.google.com/search?q=cats) to see cats pictures.  
        
