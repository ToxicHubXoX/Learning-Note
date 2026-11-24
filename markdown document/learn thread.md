# MarkDown Learn Thread

- Tutorial source: [Tutorial Site](https://www.markdownguide.org/)
- Learning reason: I want to write my learning note by using markdown

# Markdown Syntax

## Heading and Paragragh

The most basic syntax of markdown is the Heading and Paragragh.  
The Heading means words will become bigger and thicker than usauly, it have six levels to choose. Levels using '#', '==' and '--' to choose.

### Headings

Headings have two ways to define the style level, one is using the '#'/number sign to specify the all six levels, and the another is using '==' and '--' to specify the first two.

1. '#'/number sign

   If using the '#' to set the Heading style, should add the "#"s in the front of your heading content, like:

   > ## HeadingContent

   > `## HeadingContent`

   And the relaship of this specified, like:

   > |Syntax Mark|Heading Style|
   > |:---:|:---:|
   > |#|h1|
   > |...|...|
   > |######|h6|

2. '==' and '--'

   If using '==' or '--' to set Heading style, that must using any number of '=' or '-' to put on the bottown of the Heading content:

   > HeadingContent
   > -----
   >
   > code:
   >
   > `HeadingContent`
   >
   > `-----`

   That mean using the h1 style to display heading content, the relaship of they two, like:

   > |Syntax Mark|Heading Style|
   > |:---:|:---:|
   > |==|h1|
   > |--|h2|

### Paragragh

The Paragragh is another basic element class. They use a blank line to split themself. And if you not use a blank line, the two paragreghs may become one， like following:

> ||Correct|Mistake|
> |:---:|:---:|:---:|
> |Code|`Paragragh1`<br><br>`Paragragh2`|`Paragragh1`<br>`Paragragh2`|
> |Display|Paragragh1<br>Paragragh2|Paragragh1Paragragh2|

### Formating Text

In the paragraghs, they have some another syntax to decorate themselves.

1. Line Break

    Line break is a kind of paragragh decorators, they'll make a new blank line in a paragraph.
    It's composed by two space ' ' with one line feed, they two following the frist line.

    > code:
    >
    > `frist line  `<br>
    > `second line`
    >
    > display:
    >
    > frist line  
    > secend line
    >

2. Bold and Italic

    Bold and Italic are literaly make the word to them style. they using star mark `*` and underline `_` make `*content*` shape to explain them.

    The number of marks to select Bold, Italic and them two, like:

    > |Code|display|
    > |:---:|---|
    > |`*Italic*`|*Italic*|
    > |`**Bold**`|**Bold**|
    > |`***Bold and Italic***`|***Bold and Italic***|

    These marks can be repalced any pair(head and tail) of star marks to underline, the display will not change.

3. Strikethrough (Availability)

4. Subscript (Availability)

5. Superscript (Availability)

## Inserts

I think the markdown have some insert aparts, in official tutorial they not call that, but I do.

The insert is a part have extra function out of no functional text display, like hyper-link(links), images and insertable graphic shape.

### Links

Links are creatable on a paragragh text, they have many type of style to display, like following:

1. Title link

2. URLs and Email

3. Formating

4. Reference-style Link

5. Heading ID Links (Availability)

### Images

### Horizontal Rule

### Heading IDs (Availability)

### Emoji (Availability)

## Blocks

### Blockquote

### List

### Code

### Table (Availability)

## Others

### Automatic URL Linking

### Escaping Form
