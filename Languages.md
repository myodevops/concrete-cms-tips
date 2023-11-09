### Concrete CMS - Tips & Tricks
[<-- Back](/README.md)

- [Languages](#languages)
  - [Languages and Global Area](#languages-and-global-area)

 
## Languages
### Languages and Global Area
In some templates, some columns of header or footer, that are in the Global Area (the area that is common to all the pages in the portal), remaining the same in the [Concrete Multilingual function](https://documentation.concretecms.org/user-guide/guided-tour/multilingual). So that, if you change the footer in the english version of your portal, it will be changed in the other languages version too.

To prevent this, you must transform each individual column of the Global Area that you want to be distinct for each language, defining it separately. To do this, simply follow the steps below:

- From the [Dashboard](https://documentation.concretecms.org/user-guide/guided-tour/dashboard), select the item Stacks & Blocks
- From the Stacks & Global Areas submenu, select the line Global Area
- A list of global columns appears. Select the object that you want to distinguish by languages
- If you have activate the [Concrete Multilingual](https://documentation.concretecms.org/user-guide/guided-tour/multilingual), the end of the breadcrumb become an option (1). You can select the language in which you want to localize the column (2). The ideal is to do this for every language except the main one: 
  
![screenshot](img/2023-11-09%2000_34_37-Window.png)

Now you can modify the global column and the effect spreads only in the pages of the language localization and not in all.