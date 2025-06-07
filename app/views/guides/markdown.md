# Markdown Files

Written by: @Taran The Idiot
---

Hello! Here I will be teaching you how to write nice looking Readmes and Journals and how to use .md files.\
This is different from the How To Ship tutorial in that this shows you how to write in markdowns whereas the other one teaches you how to properly ship your project.

## Contents

1. [Titles](#title)



## Basics

First we go over the basic things you need to know when making a markdown

### Titles {#title}

Titles separate large chunks of text into sections.\
Sure you can just make these the size of a normal line but that doesnt really do an effective job at separation, especially when some titles are more important than others.

To add a title to your Markdown, put a hashtag before the title.\
It should look like this: `# title`\
Make sure there is a space between the hashtag and title, otherwise it will look like\
#title\
which is not what you want.

To add stuff like subheadings, add more hashtags.\
`## h2` `### h3` and so on and so forth.

Its pretty easy once you get the hang of it.

### New Lines

You cant just press the enter key to start a new line in a markdown.\
You need to use these things called backward slashes. Its like a forward slash, but backwards.

```
hi\
how are you?
```
This is what it looks like to use a backward slash.\
You should still press enter between lines so its easier to read when editing.\
The Backward Slash can be found above the enter button.

If you dont put back slashes, your sentences would look like this:\
hi
how are you?
I am great thanks!

#### Paragraph breaks

To create a break for a paragraph you just press enter twice\
```
hi

How are you?
```
You dont put a backward slash on the last line of a paragraph, it wont do anything and you will be able to see the slash in the markdown.

### Images

![image](/app/assets/images/logo.png)

Images are really important for a good readme and journal. But you can't just drop them in like a google doc, you need to add them into your repo and link them in.

First make an assets folder in your repo and put all your screenshots and photos inside there\
![screenie](/app/assets/images/markdownimage.png)\
your repo should look somewhat like that. Maybe not as many images but should have the same structure.

Next you can link your image into the markdown file.\
Use this line:
```
![alt text](assets/image.png)
```

alt text should be a one word describer for the image. It is usually hidden but shows if the image fails to load. Always keep this in square brackets.\
Next assets/image.png is the filepath for the image. Keep this in curved brackets.\
If you have multiple images in a row, you need to put back slashes to separate them similar to normal text.

### Formatting

Woah, you wanna put ilalics and make your text bold, add code blocks and quotes? well look no further.

#### Italics (aka slanted text)

To put your text in *italics*, you need to add * to each end.\
Like so:\
`*hi*`

*This makes the text Italic.*

#### Bold (thick text)

To make your text **bold**, add ** to each end.\
Like so:\
`**hi**`

**This makes your text bold**

#### Code Blocks

You have seen throughout this guide where I add the raw code and the places I put it look different.\
How do I do this?\
Through codeblocks.

To use a code block, put `s on either end of the line.\
Like so:\
``hi``

```
You can find this above the tab button
It is not an apostrophe
```

To add a big block of code that takes up multiple lines like above, use ``` on the line above and line below\
Like so:\
~~~
```
hi
You can write multiple lines of code here
its good for showing snippets of code
```
~~~

You can use ~ instead of ` but I find the second one easier to use.

#### Quotes

To add a quote, use > in front of the line with a space.\
`> There are weirdos in every breed`

> This makes the text look like this
