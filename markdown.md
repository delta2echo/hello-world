

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


