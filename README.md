# Instructions

Here are short instructions how to edit and add pages.

## Basic editing

Note, that this repository is *PUBLIC*, because otherwise it would cost money. Never put any secret files into this repository.

To edit a file, you must first have access to the repository.

When you have access, go to the repository root. Select the file you want to edit. 
You will go to a screen that shows the content. From this page, you can click on the 
pen symbol to edit the file.

Do not remove the top stuff between three slashes (including them). Otherwise you can do whatever you want. If you want to
change the title, change the text after "title:" on top.

You can just write stuff and put them in paragraphs as you wish. You can use markdown markup to simply add some 
special effects.

Lines that have two hash symbols (##) will be subtitles. If line starts with star (*), then it will be a list of bullets.

Other formatting you can learn from this document:

https://guides.github.com/features/mastering-markdown/

When you are done editing, just push the button commit the changes. The changes will be visible in a short while. You can keep
the default selection "Commit to the master branch".

## Adding a new page

Go to the repository page. Push button "Create a new file".

Give it a short name, and add "_fi.md" to the name. For example "zzz_fi.md". This means it is the Finnish version.
The pages are ordered, and the home page is named "index", so it will be first on top as long as nothing is before 
it in the alphabet.

Copy the following text to the top of the file:

```
---
lang: fi
layout: default
title: Zzz
---
```

The title will be shown both at the top of the article as well as on the left navigation.

The navigation is created automatically for both languages, and depends on the value (what is after the colon) of the lang.

Then create a English version page similarly, but name it "_en.md", and instead of "lang: fi", put "lang: en".

If you want, you can also add "navi: Z". In this case this is the title we show in the navigation bar, whereas title is
on the top of the page.

That's it!
