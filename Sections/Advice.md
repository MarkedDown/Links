
# Advice

<br>

It is usually recommendable to use `Referenced` links as <br>
they can move the clutter - their **URL**s - into a dedicated <br>
section and making your documentation more readable.

<br>
<br>

## Example

The following paragraph isn't very readable despite <br>
the links not even containing any query parameters.

<br>

```markdown
XYZ comes with a comprehensive **[API](https://organization.github.io/project/docs)** as well as <br>
the ability to integrate with **[Moodle](https://moodle.org/)** / [Canvas](https://its.sdsu.edu/tools/canvas).
```

<br>

***It can be turned into:***

<br>

```markdown
Comes with a comprehensive **[API]** as well as <br>
the ability to integrate with **[Moodle]** / **[Canvas]**.
```

<div align = 'center'>

**+**

</div>

```markdown
[Moodle]: https://moodle.org/
[Canvas]: https://its.sdsu.edu/tools/canvas
[API]: https://organization.github.io/project/docs
```

<br>
<br>

## Placement

You may want to simply group your links into local collections <br>
on a `Per-Paragraph` basis or instead have a **[Link Section]**.

<br>
<br>


<!----------------------------------------------------------------------------->

[Link Section]: ./Link%20Section.md