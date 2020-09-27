---?color=#09868B

@snap[north]

#### What is markdown (MD)

@snapend

@snap[midpoint text-08 fragment]

@color[orange](Markdown is a lightweight markup language with plain-text-formatting syntax)

@snapend

Note:

plain text power  
generate (convert) - doc, pdf, publishers(books)

---?color=#09868B

@snap[north]

#### Real world application examples

@snapend

@snap[west text-08 fragment]

- Configs
- Infrastructure as Code
- Documentation + self generated
- Documents
- Presentations - @color[green](e.g this one)

@snapend

@snap[east text-08 fragment]

- Flow diagrams (mermaid)
- CMS - e.g. grav
- Master's thesis
- Books
- ...

@snapend

Note:

Master's thesis - Dissertation  
CMS - Content management system

---?color=#09868B

@snap[north]

#### Markdown flavors (36)

@snapend

1. Markdown
2. Markdown 2
3. GitHub Flavored Markdown
4. GitLab Flavored Markdown (GFM)
5. Pandoc
6. ...

---?color=#09868B

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

---?color=#09868B

@snap[north]

#### MD elements - @color[red](advanced)

@snapend

- footnotes
- math
- diagrams and flowcharts
- inline HTML
- ....

---?color=#09868B

#### @color[orange](MD element) examples

---?color=#09868B

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

---?color=#09868B

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

---?color=#09868B

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

@snap[east bg-blue text-left text-white fragment text-06]

_Italic text_

**Bold text**

_You **can** combine them_

@snapend

---?color=#09868B

@snap[north]

#### backslash escapes

Markdown will not rendered character after backslash
\*asterisks, not italic\* => _asterisks, not italic_

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

---?color=#09868B

#### fence code blocks

```javascript
const store = createStore(reducer);
function reducer(state = [], action) {
  return "x";
}
```

Note:

Code above will be converted into code block
with javascript syntax highlighting

---?color=#09868B

@snap[north]

#### headers

@snapend

@div[left-50]

```markdown
#### This is header 4

##### This is header 5

###### This is header 6, in HTML <h6>
```

@divend

@div[right-50 text-left fragment]

#### This is header 4

##### This is header 5

###### This is header 6

@divend

---?color=#09868B

@snap[north]

#### images

```markdown
Format: \!\[Alt text\](url)

\!\[Medium Logo\](https://cdn-medium.com/max/400/1*Q9G3pLrxbX9-w.png)
```

@snapend

@snap[south fragment]

![Medium Logo](https://cdn-images-1.medium.com/max/400/1*QnlI8nTg-t9G3pLrxbX9-w.png)

@snapend

---?color=#09868B

@snap[north]

#### lists

@snapend

@snap[west text-06 text-left]

```markdown
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
```

@snapend

---?color=#202020

@snap[north]

#### lists

@snapend

@snap[west text-05 text-left]

Unordered list

- first
- second
  - first in second, yes you can make nested list
  - second in second

<br><br>

Ordered list

1. one
2. two
3. three
   - Also yes, you can combine unordered with ordered list
   - Just give three spaces and your list will be nested
   - How cool and easy

@snapend

---?color=#09868B

@snap[north]

#### tables

@snapend

@snap[west text-right]

```markdown
| No  | Name        |
| :-- | ----------- |
| 1.  | Jundi Alwan |
| 1.  | John Doe    |
```

@snapend

@snap[east text-left fragment text-06]

| No  | Name        |
| :-- | ----------- |
| 1   | Jundi Alwan |
| 2   | John Doe    |

@snapend

Note:

limited - simple one row tables

---?color=#09868B

#### Resources

1. full MD element reference list
   <https://docs.gitlab.com/ce/user/markdown.html>

1. self paced git learning
   <https://www.markdowntutorial.com/>

1. <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>
1. <https://docs.gitlab.com/ce/user/markdown.html>

---?color=#09868B

## @color[blue](Q) / @color[green](A) ?

---?color=#09868B

#### references

1. <https://github.com/commonmark/commonmark-spec/wiki/markdown-flavors>
1. <https://docs.gitlab.com/ce/user/markdown.html>
1. <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>
