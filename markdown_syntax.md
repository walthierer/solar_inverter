# Markdown Syntax

## Typography
### Headers

```
# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading
```

### Emphasis 

**This is bold text**  
__This is bold text__
```
**This is bold text**
__This is bold text__
```

*This is italic text*  
_This is italic text_
```
*This is italic text*
_This is italic text_
```
~~crossed out text~~  
`~~crossed out text~~`

### Line Breaks
Markdown doesn't always add line breaks. Use __two spaces__ before the line break to start the next line. 

## Lists
### Ordered List
1. Item one
2. Item two
3. Item three
```
1. Item one
2. Item two
```

### Unorderd List
+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces (or via tab key):
  - Marker character change forces new list start:
    * you can use
    + any markdown Bullet Points 
    - inside your list
+ Very easy!

```
+ Sub-lists are made by indenting 2 spaces (or via tab key):
  - Marker character change forces new list start:
    * you can use
    + any markdown Bullet Points 
    - inside your list
```

### ToDo List
- [ ] ToDos
  - [x] Buy some salad
  - [ ] Brush teeth
  - [x] Drink some water
  - [ ] Have a look at the source code and mark this ToDo with a x
     
```
- [ ] ToDos
  - [x] Buy some salad
```

## Embeded Link

[ASKnet Website](https://asknet.community/)  
`[link text](https:// "title")`

## Images

You can embed images by giving them a description followed by the URL of the image itself.  
![ASKnet Logo](https://raw.githubusercontent.com/ASKnetCommunity/OER_documents_template/main/images/asknet-logo.png)  
`![description](URL)`

## Code Snippets

You can highlight code snippets or anything else by using the: ` `` `  
Three in a row allows you to select a block instead of a line:  
```
```higlighted text```
```
Using these code snippets on GitHub, for example, allows you to easily copy the content.  

## Tables

The colon in the second line controls the alignment of the text. In this case it is right justified, without a colon the text is left justified by default, two colons - left and right - centre the content. 
| this is a Table | second column |
| - | -: |
| first line | yes| 
| second line | hello |

```
| this is a Table | second column |
| - | -: |
| first line | yes| 
| second line | hello |
```

## Emoji

You can type any emoji like this :smile: :smiley: :cry: :wink:
`:smile: :smiley: :cry: :wink:`
> See full emoji list [here](https://www.webfx.com/tools/emoji-cheat-sheet/).
