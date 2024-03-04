
# Table of Contents
1. [Headings](#Headings)
2. [Alternate Syntax for Heading](#AlternateSyntaxforHeading)
3. [Emphasis](#emphasis)
   1. [Bold Text](#BoldText)
   2. [Italic Text](#ItalicText)
   3. [Bold and Italic](#BoldandItalic)
   4. [Blockquotes](#Blockquotes)
   5. [Blockquotes with Multiple Paragraphs](#BlockquoteswithMultipleParagraphs)
   6. [Nested Blockquotes](#NestedBlockquotes)
   7. [Blockquotes with Other Elements](#BlockquoteswithOtherElements)
4. [Lists](#Lists)
   1. [Order List](#OrderList)
   2. [Nested Listed](#NestedListed)
   3. [Unordered Lists](#UnorderedLists)
   4. [Adding Elements in a List](#AddingElementsinaList)
      1. [Blockquotes in a List](#BlockquotesinaList)
      2. [Code Blocks](#CodeBlocks)
      3. [Images](#Images)
      4. [Unordered List in an Order List](#UnorderedListinanOrderList)
5. [Code](#Code)
   1. [Inline Code](#InlineCode)
   2. [Code Blocks](#CodeBlocks)

---


<a name="GreekLetters"></a>
# Headings 

# Headings Level 1
`# Heading Level 1`

## Headings Level 2
`## Heading Level 2`

### Headings Level 3
`### Heading Level 3`

#### Headings Level 4
`####Heading Level 4`

##### Headings Level 5
`##### Heading Level 5`

###### Headings Level 6
`###### Heading Level 6`

<a name="AlternateSyntaxforHeading"></a>
# Alternate Syntax for Heading 

<h1>Heading Level 1 </h1>

`<h1>Heading Level 1 </h1>`

<h2>Heading Level 1 </h2>

`<h2>Heading Level 2 </h2>`

<h3>Heading Level 3 </h3>

`<h3>Heading Level 3 </h3>`

<a name="emphasis"></a>
# Emphasis

<a name="BoldText"></a>
## Bold Text

I just love **bold text**

`I just love **bold text**`

<a name="ItalicText"></a>
## Italic

Italicized text is the *cat's meow*

`Italicized text is the *cat's meow*`

<a name="BoldandItalic"></a>
## Bold and Italic 

This text is ***really important***.

`This text is ***really important***.`

<a name="Blockquotes"></a>
## Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.

`> Dorothy followed her through many of the beautiful rooms in her castle.`

<a name="BlockquoteswithMultipleParagraphs"></a>
## Blockquotes with Multiple Paragraphs

>Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

```
>Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

<a name="NestedBlockquotes"></a>
## Nested Blockquotes 

>Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


```
>Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

<a name="BlockquoteswithOtherElements"></a>
## Blockquotes with Other Elements

>  #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

<a name="Lists"></a>
# Lists 


<a name="OrderList"></a>
## Order List 

1. First item
2. Second item
3. third item
4. fourth item

```
1. First item
2. Second item
3. third item
4. fourth item
```

1. First item
8. Second item
12. Third item
3. Fourth item

```
1. First item
8. Second item
12. Third item
3. Fourth item
```

<a name="NestedListed"></a>
## Nested Listed
1. First item
2. Second item
3. Third item
    1. Sub First item
   2. Sub Second item
3. Fourth item

```
1. First item
2. Second item
3. Third item
    1. Sub First item
   2. Sub Second item
3. Fourth item
```

<a name="UnorderedLists"></a>
## Unordered Lists
- First item
- Second item
- Third item
- Fourth item

```
- First item
- Second item
- Third item
- Fourth item
```

Or you can use the `*` symbol to make an unordered Lists

* First item
* Second item
* Third item
* Fourth item

```
* First item
* Second item
* Third item
* Fourth item
```


<a name="AddingElementsinaList"></a>
## Adding Elements in a List


<a name="BlockquotesinaList"></a>
### Blockquotes in a List

* This is the first list item.
* Here's the second list item.
   >   A blockquote would look great below the second list item
* And here's the third list item.

```
* This is the first list item.
* Here's the second list item.
   >   A blockquote would look great below the second list item
* And here's the third list item.
```

<a name="CodeBlocks"></a>
### Code Blocks

Code blocks are normally indented four spaces or one tab. When they are in a list,indent them eight spaces or two tabs.

1. Open the file.
2. FInd the  following code block on line 21:

        for ii in List_element:
            print(ii)
3. Update the sequence from List_elements to new List_element_V2

```
1. Open the file.
2. FInd the  following code block on line 21:

        for ii in List_element:
            print(ii)
3. Update the sequence from List_elements to new List_element_V2
```


<a name="Images"></a>
### Images

1. open the file containing the Linux mascot.
2. Marvel at its beauty.

   ![Tux, the Linux mascot](../assets/tux.jpg)

3. Close the file

```
1. open the file containing the Linux mascot.
2. Marvel at its beauty.

   ![Tux, the Linux mascot](../assets/tux.jpg)

3. Close the file
```


<a name="UnorderedListinanOrderList"></a>
### Unordered List in an Order List

1. first item
2. Second item
3. third item
   - Indented item
   - Indented item
4. Fourth item

```
1. first item
2. Second item
3. third item
   - Indented item
   - Indented item
4. Fourth item
```


<a name="Code"></a>
# Code


<a name="InlineCode"></a>
## Inline Code

At the command prompt,type `nano`.

``At the command prompt,type `nano`.``

<a name="CodeBlocks"></a>
## Code Blocks

```python
for ii in List:
    print(ii)
    if ii > 10:
        print(ii + "is bigger then 10")
```

```
```python
for ii in List:
    print(ii)
    if ii > 10:
        print(ii + "is bigger then 10") 
     ```
```


