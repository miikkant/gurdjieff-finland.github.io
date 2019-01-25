# Instructions

Here are short instructions how to edit and add pages.

## How it all works out

GitHub provides a repository, which is a place where anybody 
with access can store and edit files. It also provides possibility 
for maintaining simple web pages. 

Web pages are generated and published automatically to our website
every time any of the files is modified in the GitHub repository. It 
typically takes few minutes for this generation and publishing to complete.

More info:

https://help.github.com/categories/github-pages-basics/

## Access

First you need write access to the repository where you are reading
these instructions from.

For this, you will need a GitHub account.

The name and email address related to GitHub account will not be visible 
on our web page. However, they will be visible to others on the 
GitHub repository if you make any changes,

So if you are unwilling to associate your email address and name with the
pages, you create an account with anonymous email address and 
invented name. Another option is that you can use Gurdjieff Editor account 
(gurdjieff-editor) I have created. For this, you can get password details 
from Mikko.

Go to:

https://github.com/login

## Directory structure

You only need to be concerned with files that end with .md. That means
they are so called markdown files.

There are two versions of each page, one for English and one for Finnish.
By convention, the file names are otherwise the same, but the 
language name is different, i.e. the filename ends with underscore and 
language name, for example nob_fi.md and nob_en.md.

## Basic editing

Note, that this repository is *PUBLIC*, because otherwise it would cost money.
Never write anything you do not wish everybody to know (for example passwords)
into this repository.

To edit a file, you must first have access to the repository. See previous
section for this.

When you have access, go to the repository root. Select the file you want to
edit.  You will go to a screen that shows the content. From this page, you can
click on the pen symbol to edit the file.

Do not remove the top stuff between three slashes (including them). Otherwise
you can do whatever you want. If you want to change the title, change the text
after "title:" on top.

You can just write stuff and put them in paragraphs as you wish. You can use
special characters called "markdown markup" to add some special effects.

Lines that have two hash symbols (##) will be subtitles. If line starts with
star (*), then it will be one item in a list of bullets.

You can also embed pictures etc. if you want.

Other formatting you can learn from this document:

https://guides.github.com/features/mastering-markdown/

When you are done editing, just push the button "Commit the changes". The
changes will be visible in a short while, usually less than a minute. 
You can keep the default selection "Commit to the master branch".

## Adding a new page

Go to the repository page. Push button "Create a new file".

Give it a short name, and add "_fi.md" to the name. For example "zzz_fi.md".
This means it is the Finnish version.

Copy the following text to the top of the file:

```
---
sort: 25
lang: fi
layout: default
title: Zzz
---
```

The value after layout should always be "default".

The pages are ordered by the sort key, ascending order. Value 25 here means it falls between 20 and 30.

You can put any text after the title. The title will be the title of the page, shown at the top of the article.

The navigation is created automatically for both languages, and depends on the value (what is after the colon) of the lang.

Then create a English version page similarly, but name it "_en.md", and instead of "lang: fi", put "lang: en".

If you want, you can also add "navi: Z". In this case this is the title we show in the navigation bar, whereas title is
on the top of the page. By default, we show the value of the title also in the navigation.

You can also modify the sort key, 

That's it!
