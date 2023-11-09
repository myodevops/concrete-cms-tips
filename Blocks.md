### Concrete CMS - Tips & Tricks
[<-- Back](/README.md)

- [Blocks](#blocks)
  - [Same height for blocks in the same row of a layout (adding a Custom Element Attribute)](#same-height-for-blocks-in-the-same-row-of-a-layout-adding-a-custom-element-attribute)
 
## Blocks
### Same height for blocks in the same row of a layout (adding a Custom Element Attribute)
If you create a layout in a section page with two or more columns and in every column you put a block with a border or a background, you may have the problem that the blocks are not allineate at the bottom, as in the follow screenshot:

![screenshot](/img/2023-11-04%2023_18_41-Window.png)

For allineate all the blocks to the bottom, you must assign the same height to all the blocks.
You can make it assigning a CSS class property to all the blocks. In Design & Block Template of every block, add the Custom Element Attribute `style="height: 100%"` (1) in the gear wheel configuration, as follow:

![screenshot](img/2023-11-04%2023_22_40-Window.png)

It is possible that sometime you can add the postfix `!mportant` to the property.
Saving and publishing, the result is the follow:

![screenshot](img/2023-11-04%2023_23_47-Window.png)