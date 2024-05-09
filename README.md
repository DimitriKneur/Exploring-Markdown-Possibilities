# Exploring-Markdown-Possibilities

Discover here some tips to help you enhance your markdown files.

Let's go !

<br>

## Add titles and subtitles

You can transform a text into a title / subtitle simply by adding `#` before it.

Let's take an example. If you write into your markdown :

` # Amazing Title 1 `

` ## Tremendous Title 2 `

` ### Breathtaking Title 3 `

<br>

Here is what will be displayed :
<br>
<br>
![](Screenshots/Headings.png)
<br>

As you can see, the more `#` you add, the lower your element will be in the title hierarchy.

<br>

## Stylize your text

| Style |   Syntax   |    Example   |    Output   |
|--------------|------------|--------------|-------------|
| Bold | `** **` or `__ __` | `__Bold text__` | **Bold text** |
|    Italic   | `* *` or `_ _` | `*Italic text*` | *Italic text* |
|Strikethrough   | `~~ ~~` | `~~Mistake~~`| ~~Mistake~~ |
|Bold and nested italic | `** **` and `_ _` | `**I have an _urgent_ notice !**`| **I have an _urgent_ notice !** |

<br>

## Add quote

To transform a text into a quote, you can simply add `>' before it.

Example : if you write 

` > "The yes needs the no to win against the no." `

<br>

The following will be displayed :

> "The yes needs the no to win against the no."

> [!NOTE]
> You can see that the quoted text is now indented and has a different color from the standard one.

<br>

## Add code

Want to add some code to your markdown file ? This is possible !

To do so, put triple backticks ``` before and after the text you want to apply the code format on.

Example : if you write

` ```
print("Hello World !")
``` `

<br>

The following will be displayed :
```
print("Hello World !")
```
<br>

## Add a text container

Pretty cool to display `some hilighted text`, isn't it ?

To do so, you just have to put ``` ` ``` before and after the text you want to highlight.

<br>

Example : if you write 

```
`some important text`
```

The following will be displayed :

`some important text`

<br>

## Add a link

You can insert a link into a markdown file by writing :

<br>

` [text_of_the_link](url) `

<br>

Example : let's say you want to add a link pointint out to this url :

`https://www.imdb.com/`

inside a text 

`IMDB`

Then you can write :

`Here is a link pointing out to the website of [IMDB](https://www.imdb.com/).`

And see the result :

Here is a link pointing out to the website of [IMDB](https://www.imdb.com/).

> [!TIP]
> If the ressource you want to create a link for is insite the repository, it is recommended to use relative links. That will make it easier for users if they navigate into your repository or clone it.
> <br>
> For example, if I want to add a link leading to a file or a folder that is in my repository :
> <br>
> ` [full_link](https://github.com/user/repository/tree/branch/folder/file) `
> <br>
> <br>
> I can use the relative link instead, and the result will be the same
> <br>
> ` [relative_link](folder/file) `
> <br>
> <br>
> If you want more information about relative links, don't hesitate to have a look at [GitHub documentation about relative links](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links).

<br>

## Add an image

You can also add an image inside a markdown file.

To do so, here is what you can write :

<br>

` ![](image_url) `

<br>

Example :

`![](https://github.com/DimitriKneur/Exploring-Markdown-Possibilities/assets/150923253/94053ab4-a2f1-4003-b634-834cae5cc00f)`

<br>

![](https://github.com/DimitriKneur/Exploring-Markdown-Possibilities/assets/150923253/94053ab4-a2f1-4003-b634-834cae5cc00f)

<br>

> [!TIP]
> Just like the link section, it is recommended to use relative links over absolute links when it is possible.

<br>

