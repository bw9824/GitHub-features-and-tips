# Intro
If you need to write documentation on GitHub but aren't sure how to use the syntax to achieve your desired layout, this guide is for you. Below, we demonstrate various Markdown syntaxes to help you format your files effectively.

# Table of Contents
1. [Content](#Content)
    1. [Heading](#Heading)
    2. [List](#List)
    3. [Horizontal line](#Horizontal-line)
    4. [Text](#Text)
    5. [New Line](#New-Line)
    6. [Text Highlight](#Text-Highlight)
2. [Table](#Table)
3. [Image](#Image)
4. [Link](#Link)
5. [Alert](#Alert)

# Content
## Heading
- Syntax
```
# Heading Level 1
.
.
###### Heading Level 6 (The Minimum)
```
- Example
#### Heading Level 4
###### Heading Level 6
[Back to Table of Contents](#table-of-contents)

## List
- Syntax
```
1. XXA List
    1. XXB List
        1. XXC List
- XXA List
    - XXB List
        - XXC List
```
- Example
1. XXA List
    1. XXB List
        1. XXC List
- XXA List
    - XXB List
        - XXC List

[Back to Table of Contents](#table-of-contents)

## Horizontal line
- Syntax
```
***
---
___
```
- Example
***
[Back to Table of Contents](#table-of-contents)

## Text
- Syntax 1    
Your Text
- Example 1  
Welcome!!!  
Thank You

- Syntax 2  
` ``` `  
Your Text  
` ``` `
- Example 2  
```
Welcome!!!
Thank You
```

- Syntax 3  
` ```c `  
Your Coding  
` ``` `
- Example 3  
```c
int function(void){
    int age = 20;
    printf("My age is:%d", age);
    return 0;
}
```
[Back to Table of Contents](#table-of-contents)

## New Line
Simply pressing 'Enter' won't create a line break. 'Adding two spaces' after the previous line of text then pressing 'Enter', which will then wrap the text to the next line.  
(Only required for Content Syntax 1**, **Content Syntax 2 can simply pressing 'Enter')

## Text Highlight

| Syntax | Example |
| ------ | ------- |
| ``` `Highlight` ``` | `Highlight` |
| `*Italic 1*`, `_Italic 2_` | *Italic 1*, _Italic 2_ |
| `**Bold 1**`, `__Bold 1__` | **Bold 2**, __Bold 2__ |
| `~~Strikethrough~~` | ~~Strikethrough~~ |
| `*__Italic Bold 1__*` | *__Italic Bold 1__* |

[Back to Table of Contents](#table-of-contents)


# Table
- Syntax
```
| Table Title 1 | Table Title 2 | Left-aligned | Center-aligned | Right-aligned |
| ------------- | ------------- | :------------ | :-----------: | ------------: |
| Table Content | A | C | E | G |
| Table Content | **B** | _D_ | ~~F~~ | **_H_** |
```
- Example

| Table Title 1 | Table Title 2 | Left-aligned | Center-aligned | Right-aligned |
| ------------- | ------------- | :------------ | :-----------: | ------------: |
| Table Content | A | C | E | G |
| Table Content | **B** | _D_ | ~~F~~ | **_H_** |

[Back to Table of Contents](#table-of-contents)

# Image
1. Click "Upload files"
2. Drag the image or GIF you want to put in README.md to the repository
3. The image or GIF uploaded to Git will have a URL
4. Commands to put the image or GIF in MD file
- Syntax
```
![image](image or GIF url)
```
- Example

![Github](https://upload.wikimedia.org/wikipedia/commons/f/ff/Logo_of_Github.jpg)

[Back to Table of Contents](#table-of-contents)

# Link
| Syntax | Example | Note |
| ------ | ------- | ---- |
| `[Github link](https://github.com/)` | [Github link](https://github.com/) |  |
| `[Github link][Github]` | [Github link][Github] | `[Github]:https://github.com` won't be displayed in the content |
| `[![](https://upload.wikimedia.org/wikipedia/commons/f/ff/Logo_of_Github.jpg)](https://github.com/)` | [![](https://upload.wikimedia.org/wikipedia/commons/f/ff/Logo_of_Github.jpg)](https://github.com/) |  |
| `[![Github Picture]][Github]` | [![Github Picture]][Github] | `[Github Picture]:https://upload.wikimedia.org/wikipedia/commons/f/ff/Logo_of_Github.jpg`   won't be displayed in the content |
| `[Example](/Example)` | [Example](/Example) | Internal file links |
| `[Heading](#Heading)` | [Heading](#Heading) | Each 'Heading' is a Link |

[Github]:https://github.com
[Github Picture]:https://upload.wikimedia.org/wikipedia/commons/f/ff/Logo_of_Github.jpg
[Back to Table of Contents](#table-of-contents)


## Alerts
- Syntax
```
> [!NOTE] or > [!TIP] or > [!IMPORTANT] or > [!WARNING] or > [!CAUTION]
Content
```
- Example

> [!NOTE]
This is a notification message

[Back to Table of Contents](#table-of-contents)
