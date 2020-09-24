### What is markdown(MD)

> Markdown is a lightweight markup language with plain-text-formatting syntax

text power
generate (covert)

---

### MD flavors

1. Markdown
2. Markdown 2
3. GitHub Flavored Markdown
4. GitLab Flavored Markdown (GFM)
5. Pandoc
6. ...

---

### MD elements - basic

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

### MD elements - advanced

- footnotes
- math
- diagrams and flowcharts
- inline HTML

---

### MD element @color[yellow](examples)

---

### task lists

```bash
- [x] this is complete item
- [ ] this is incomplete item
```

- [x] this is complete item
- [ ] this is incomplete item

---

### links

```bash
Format: [Placeholder](url) OR just paste the link with http
and it automatically turns into link

[Medium](http://medium.com)
```

[Medium](http://medium.com)

---

### blockquotes

```bash
Format: > Words you quotes

Like he said:
> Happiness can be found even in the darkest of times,
> if one only remembers to turn on the light.
```

---

### emphasis

```bash
*Italic text*
_Italic text too_

**Bold text**
__Bold text too__

*Of course you **can** combine them*
```

_Italic text_
_Italic text too_

**Bold text**
**Bold text too**

_Of course you **can** combine them_

---

### backslash escapes

```bash
To tell markdown too not rendered the character after backslash
\*Just asterisks, not italic\* => *Just asterisks, not italic*
```

---

### backslash escapes - table

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

---

### fence code blocks

```javascript
const store = createStore(reducer);
function reducer(state = [], action)
{ return 'x' };

Code above will be converted into code block with javascript syntax highlighting

```

---

### headers

```bash
# This is header 1
## This is header 2
###### This in header 6, the smallest header as you know in HTML syntax as <h6>
```

# This is header 1

## This is header 2

###### This in header 6

---

### images

```bash
Format: ![Alt text](url)
![Medium Logo](https://cdn-images-1.medium.com/max/400/1*QnlI8nTg-t9G3pLrxbX9-w.png)
```

---

### lists

```bash
Unordered list
* first
* second
   * first in second, yes you can make nested list
   * second in second

Ordered list
1. one
1. two
1. three
   * Also yes, you can combine unordered with ordered list
   * Just give three spaces and your list will be nested
   * How cool and easy
```

Unordered list

- first
- second
  - first in second, yes you can make nested list
  - second in second

Ordered list

1. one
1. two
1. three
   - Also yes, you can combine unordered with ordered list
   - Just give three spaces and your list will be nested
   - How cool and easy

---

### tables

```bash
|No | Name       |
|---|------------|
|1  | Jundi Alwan|
|2  | John Doe   |
```

| No  | Name        |
| --- | ----------- |
| 1   | Jundi Alwan |
| 2   | John Doe    |

Note:

limited - simple one row tables

---

full MD element reference list:
https://docs.gitlab.com/ce/user/markdown.html

---

### Resources

self paced git learning
https://www.markdowntutorial.com/

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
https://docs.gitlab.com/ce/user/markdown.html

---

### references

https://github.com/commonmark/commonmark-spec/wiki/markdown-flavors
https://docs.gitlab.com/ce/user/markdown.html
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
