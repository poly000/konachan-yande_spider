# booru_spider
This is a booru spider script

[zh_CN.ver](README_cn.md)

needs packages `aria2` `kdialog`

CLI.ver: `aria2` `curl`

<br>

It's a booru spider script.

able to get: Konachan, Danbooru, Yande.re

able to filter: Questionable|Explicit|Safe

[CLI Update History](#cliverhistory)

# Update History

* v1.3.1

 edited output
 
 fix: danbooru able to search tags
 
* v1.3.0
 
 no more jq needs
 
* v1.2.2

 danbooru able to search tags

* v1.2.1

 filters added
 
* v1.2.0

 fixed tags no result or one page only then error

* v1.1.1

 fixed no selected booru then error
 
 fixed tags no result or one page only then until do-loop

* v1.1.0

 fixed gets tags_page
 
 fixed save to file

* v1.1.0b

 added background run & stderr out，

 fixed a function including，fixed tags search first page only，

 able to run out console（select output to where）

* v1.0.6

 fixed kdialog outing error

* v1.0.5b

 used kdialog

* v1.0.4

 able to get Danbooru

* v1.0.3

 some changes
 
 renamed valuename

* v1.0.2

 some changes

* v1.0.1

 fixed "page_max"

* v1.0.0

 able to search tags

# cliverhistory

* CLI-1.3.1

 edited output
 
 fix: danbooru able to search tags
 
* CLI-1.3
 
 no more jq needs
 
 <b>use [Git for Windows](https://git-scm.com/download/win) & [aria2](https://github.com/aria2/aria2/releases) then you can run it on shitty windows</b>
 
* CLI-1.2

 some changes
 
 filters added
 
 danbooru able to search tags
 
 outfile able to rename

* v1.0.5b > CLI-1.1

 deleted some '\n'

 some changes
