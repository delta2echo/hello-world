

## Markdown tutorial:

Headers are made with 1 or more hashes "#"<br>
# 1 Hash
## 2 Hash
### 3 Hash
#### 4 Hash 
<br><br><br>

### line breaks
testing line break no_space
this is has no space

testing line break w/2spaces  
this has 2 spaces 

testing line break with break <br>
this has a break 

### bold and italics
double asterick "\*\*text\*\*" lets you **bold**<br>
midword can be b**olde**d like this "t\*\*ex\*\*t" 

single asteric "\*text\*" lets you *italisize*
midword can be ital*isize*

triple asteric "\*\*\*text\*\*\*" lets you ***bold and italisize***

### Blockquotes
> bracket "\>" creates a blockquote
>
> it must be aded to each line


[exampleplot]:data:
> this is a
>> nested <br>
>>>block quote

### Lists 

#### unordered lists
"\-", "+", "*" can be used to make unordered list:<br>
- dash
+ plus 
* asterick
- bullets 
    - can also be nested
        - like this 

#### ordered lists
Numbers (1,2,3...) are used to make an ordered list 
1. Like
2. this
    3. they can
        4. be nested
3. but they dont need
4. to be in order numerically
1. any 
1. number 
1. will
1. do


1. to add a<br>
    new line to a<br>
    bullet element
2. do it<br>
    like<br>
    this

3. a blockquote
    > can also be added


### Code blocks
are created by indenting with 1 tab or 4 spaces

    import matplotlib.pyplot as plt


    fig, ax = plt.subplots(1,1)
    ax.plot([i for i in range(10)],[i**2 for i in range(10)])
    fig.suptitle('example plot')

    fig.savefig('../markdown/testplot.png')


### images

are created with this syntax: "\!\[description](pathfile)"

![example plot](testplot.png?raw=true)

![example plot][exampleplot]

![example plot](https://drive.google.com/file/d/1fjrSUwM4D04bYxAB7iuCtgSs62DrZXw3/view?usp=sharing "example")

<img class="right" src="https://drive.google.com/file/d/1fjrSUwM4D04bYxAB7iuCtgSs62DrZXw3/view?usp=sharing" alt="example plot">


### hyperlinks

Hyperlinks are created like this: \[display text](link "hover text")<br>
[google](https://google.com "This links to google")

this also works for a quick link: \<url><br>
<https://google.com>

emphasize links just like text:<br>
***[google](https://google.com)***


its also possible to create footnote links:<br>

    [google][1]<br>
    [duckduckgo][2]<br>
    [bing][3]
    
    [1]: https://google.com
    [2]: https://duckduckgo.com
    [3]: https://bing.com "this links to bing"

[google][1]<br>
[duckduckgo][2]<br>
[bing][3]

[1]: https://google.com
[2]: https://duckduckgo.com
[3]: https://bing.com "this links to bing"


###Escape Characters

backslashes are used as an escape character \\ 
and allow formatting characters to be displayed as text<br>
\#<br>
\><br>
\\<br>
\+<br>



[exampleplot]:data:image/png;base64,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
