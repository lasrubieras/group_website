# Group Website
This is a repository for learning how to make webpages with Jekyll Pages 
This is from my participation in The Carpentries workshop.

When I want to have **bold** text, we use two asteriks around the bolded text.
To use _italics_, we can use underscores or a single asterik.  
If I want to print a \*, one can escape it? \*\*not bolded\*\*.


## Section 2

This is the first paragraph of this section. Simple formatting can be inserted simple by wrapping the text we want to formatwith asteriks. 
Simple pressing enter and moving to the next line does not insert a separating line between paragraphs.
An extra pair of spaces after the end of the lines does does the trick tho.  
See? You can see the line break now. 

A blank lines does insert a separator between paragraphs.

List are make by starting a line with a dash 

- item 1
- item 2
- item 3 
- item n

Numbered lists start with a number. MD will figure out the sequencing. Any number will do 

1. item 1
1. item 2
1. item 3
2. item 4
25. item 5


Codes can be fenced offf by three backticks \`\`\`

``` print("Hello world")```

It can be inserted inline embedding it within the text. Use single backticks for that.  
Here we need to use a `print()` call. 

The code isn't specific to an language in particular, but it can be done by writing the language right after the first set of backticks
``` python
  print("Hellow World!")
```

## More code snippets example

``` python
  s = "How are you?"
  print(s)
```

``` R
  print(paste("How", "are", "you?"), quote = FALSE)
```

``` html
<!DOCTYPE html>
 <html>
   <body>
     <a href=hhtps://carpentries.org/>This is a link</a>
   </body>
 </html>
```

## How to do links in MD?

[The Carpentries](https://carpentries.org)

It is possible to create a tag for subsequent use in the document

[carpentries-tag]: https://carpentries.org

So I would like you to visit [this link][carpentries-tag]

Example links:
1. [Inline link](https://carpentries.org/)
2. Follow [Reference link][case-insensitive-reference-tag]

[case-insensitive-reference-tag]: https://carpentries.org/ 



