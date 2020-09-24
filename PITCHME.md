@snap[north]

#### What is markdown (MD)

@snapend

@snap[midpoint text-08 fragment]

@color[orange](Markdown is a lightweight markup language with plain-text-formatting syntax)

@snapend

Note:

text power  
generate (convert)

---

@snap[north]

#### MD flavors

@snapend

1. Markdown
2. Markdown 2
3. GitHub Flavored Markdown
4. GitLab Flavored Markdown (GFM)
5. Pandoc
6. ...

---

@snap[north]

#### MD elements - @color[green](basic)

@snapend

- table of contents - TOC
- superscripts / subscripts
- inline code
- reference by e.g. username, issue, MR, ...
- videos
- audio
- ....

Note:

reference by - !, #, @

---

@snap[north]

#### MD elements - @color[red](advanced)

@snapend

- footnotes
- math
- diagrams and flowcharts
- inline HTML

---

#### @color[orange](MD element) examples

---

@snap[north]

#### task lists

@snapend

@snap[west]

```markdown
- [x] this is complete item
- [ ] this is incomplete item
```

@snapend

@snap[east fragment text-06]

- [x] this is complete item
- [ ] this is incomplete item

@snapend

---

@snap[north]

#### links

@snapend

@snap[west text-06]

```markdown
Format: \[Placeholder\](url) OR
just paste the link with http and
it automatically turns into link

\[Medium\](http://medium.com)
```

@snapend

@snap[east fragment text-06]

[Medium](http://medium.com)

@snapend

---

@snap[north]

#### blockquotes

@snapend

@snap[west]

```markdown
Format: > Words you quotes

Like he said:

> Happiness can be found even
> in the darkest of times,
> if one only remembers
> to turn on the light.
```

@snapend

@snap[east bg-blue text-left fragment text-06]

Like he said:

> Happiness can be found even
> in the darkest of times,
> if one only remembers
> to turn on the light.

@snapend

---

@snap[north]

#### emphasis

@snapend

@snap[west]

```markdown
_Italic text_

**Bold text**

_You **can** combine them_
```

@snapend

@snap[east bg-blue text-left fragment text-06]

_Italic text_

**Bold text**

_You **can** combine them_

@snapend

---

@snap[north text-07]

#### backslash escapes

```markdown
To tell markdown too not rendered the character after backslash
\*Just asterisks, not italic\* => _Just asterisks, not italic_
```

@snapend

@snap[south text-05 fragment]

<br><br><br>

| symbol | name             |
| :----: | :--------------- |
|   \    | backslash        |
|   `    | back tick        |
|   \*   | asterisks        |
|   \_   | underscore       |
|   {}   | curly braces     |
|   []   | square brackets  |
|   ()   | parentheses      |
|   \#   | hash mark        |
|   +    | plus sign        |
|   -    | minus sign       |
|   .    | dot              |
|   !    | exclamation mark |

@snapend

---

#### fence code blocks

```javascript
const store = createStore(reducer);
function reducer(state = [], action)
{ return 'x' };

Code above will be converted into code block
with javascript syntax highlighting

```

---

@snap[north]

#### headers

@snapend

@snap[west]

```markdown
#### This is header 4

##### This is header 5

###### This in header 6, in HTML <h6>
```

@snapend

@snap[east text-left fragment]

#### This is header 4

##### This is header 5

###### This in header 6

@snapend

---

#### images

```markdown
Format: ![Alt text](url)

\![Medium Logo](https://cdn-images-1.medium.com/max/400/1*QnlI8nTg-t9G3pLrxbX9-w.png)
```

![Medium Logo](https://cdn-images-1.medium.com/max/400/1*QnlI8nTg-t9G3pLrxbX9-w.png)

---

@snap[north]

#### lists

@snapend

@snap[midpoint fragment]

```markdown
Unordered list

- first
- second
  - first in second, yes you can make nested list
  - second in second

Ordered list

1. one
2. two
3. three
   - Also yes, you can combine unordered with ordered list
   - Just give three spaces and your list will be nested
   - How cool and easy
```

@snapend

@snap[midpoint fragment]

Unordered list

- first
- second
  - first in second, yes you can make nested list
  - second in second

Ordered list

1. one
2. two
3. three
   - Also yes, you can combine unordered with ordered list
   - Just give three spaces and your list will be nested
   - How cool and easy

@snapend

---

@snap[north]

#### tables

@snapend

@snap[west text-right]

```markdown
| No  | Name        |
| --- | ----------- |
| 1   | Jundi Alwan |
| 2   | John Doe    |
```

@snapend

@snap[east text-left fragment text-06]

| No  | Name        |
| --- | ----------- |
| 1   | Jundi Alwan |
| 2   | John Doe    |

@snapend

Note:

limited - simple one row tables

---

#### Resources

1. full MD element reference list
   https://docs.gitlab.com/ce/user/markdown.html

1. self paced git learning
   https://www.markdowntutorial.com/

1. https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
1. https://docs.gitlab.com/ce/user/markdown.html

---

#### references

1. https://github.com/commonmark/commonmark-spec/wiki/markdown-flavors
1. https://docs.gitlab.com/ce/user/markdown.html
1. https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
