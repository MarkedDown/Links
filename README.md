
<div align = 'center'>
         
# Links
         
<br>

**Markdown** links can be categorized into `Raw` & `Referenced` links.

</div>
         
<br>

#### Raw

Links of this type place the `URL` close to their declaration.

<br>

#### Referenced

With this type, the links' value can be decoupled from it's <br>
declaration which allows it to be placed wherever desired.

<br>
<br>
<br>

<div align = 'center'>

## Examples
         
</div>

<br>

### Ｒａｗ

```md
You are required to install the **Blinker** library
from https://github.com/blinker-iot/blinker-library
```

<div align = 'center'>

**Or**

</div>
         
```md
You are required to install the **[Blinker](https://github.com/blinker-iot/blinker-library)** library.
```

<br>

### Ｒｅｆｅｒｅｎｃｅｄ

```md
You are required to install the **[Blinker]** library.
```

<div align = 'center'>

**+**

</div>

```md
[Blinker]: https://github.com/blinker-iot/blinker-library
```

<br>
<br>
<br>

<div align = 'center'>

## Advice
         
</div>

<br>

I would almost always ***`recommend to use Referenced Links`*** , <br>
as they can move the clutter - that is their **URL** - into a dedicated<br>
section and thus make your documentation more readable.

<br>

##### Let Me Give You An Example

This not very readable example paragraph, whos links don't <br>
even contain any parameters, can be significantly tidied up

<br>

```md
XYZ comes with a comprehensize **[API](https://organization.github.io/project/docs)** as well as <br>
the ability to integrate with **[Moodle](https://moodle.org/)** / [Canvas](https://its.sdsu.edu/tools/canvas).
```

<br>

into 2 readable section, such as

<br>

```md
Comes with a comprehensive **[API]** as well as <br>
the ability to integrate with **[Moodle]** / **[Canvas]**.
```

<div align = 'center'>

**+**

</div>

```md
[Moodle]: https://moodle.org/
[Canvas]: https://its.sdsu.edu/tools/canvas
[API]: https://organization.github.io/project/docs
```

<br>

##### Where To Put The Links

You may want to simply group your links into local collections <br>
on a `Per-Paragraph` basis or instead have a `Link Section` .

<br>
<br>

<div align = 'center'>

## Link Section
         
</div>

<br>

If you want to have a central place in your document to place <br>
your links, you will want to create a dedicated section for it.

You could place it anywhere in your project, though obviously <br>
at the top / bottom would seem the most sensible for this.

In this case I would strongly ***`encourage to place it At The Bottom`*** <br>
as otherwise you will have to traverse it every time you want ot edit the file.

<br>

### Example

```md

Thank you for reading till the end of this Readme.

<!----------------------------------------------------------------------------->

[Moodle]: https://moodle.org/
[Canvas]: https://its.sdsu.edu/tools/canvas
[API]: https://organization.github.io/project/docs
```


<br>
<br>
<br>

<div align = 'center'>

## Separators
         
</div>

In the above example you saw a separator comment / line being used, <br>
I'd recommend this to mark the start / end of such `Meta-Sections`.

<br>

### Width

As in general, with human readble text, you will <br>
want to stay in the `60 - 80` columns range, so <br>
you should with a separators width.

*Your editor of choice probably already* <br>
*has a limit or line that indicates this limit.*

<br>

### Design

<br>

**Be creative!** <br>
***Here are some examples:***

<br>
<br>

**Generic**

<div align = 'center'>

```md
<!----------------------------------------------------------------------------->
```
         
</div>
<br>
<br>

**Wavy**

<div align = 'center'>

```md
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
```

</div>
<br>
<br>

**With Lables**

<div align = 'center'>

```md
<!----------------------------------[ Badges ]--------------------------------->
```

</div>
<br>
<br>

**Left Aligned + [Tortoise Brackets]**

<div align = 'center'>

```md
<!--⦗ Social Media ⦘----------------------------------------------------------->
```

</div>
<br>
<br>

**Using [Box] Characters**

<div align = 'center'>

```md
<!--╼━━┯━━━━━━━━┯━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓   
         │ Contributors │                                                   ┃   
         └──────────────┘                                                   ┖-->
```

</div>
<br>
<br>

**Classic `+`**

<div align = 'center'>

```md
<!--+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-->
<!--+                          Design Documentation                         +-->
<!--+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-->
```

</div>
<br>


<!----------------------------------------------------------------------------->

[Tortoise Brackets]: https://unicode-table.com/en/2997/
[Box]: https://unicode-table.com/en/blocks/box-drawing/
