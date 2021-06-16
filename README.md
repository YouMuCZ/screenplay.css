# screenplay.css

A Stylesheet Replicating Screenplays

---

[Demo](screenplay.higby.io) using Nicholl Fellowship script sample

## Usage

This was made specifically for use with markdown:

| Element        | Screenplay Equivalent |
|----------------|-----------------------|
| h1             | Title                 |
| h2             | Scene Heading         |
| h3             | Left Transition       |
| h4             | Centered Text         |
| h5             | Transition            |
| hr             | Print Page Break      |
| Defintion List | Attribution           |
| blockquote     | Note                  |
| Dialogue*      | List                  |
| Parenthetical  | List Blockquote       |
| Mark, Code     | Highlighted Text      |
| <address>**    | Address               |

> * First list item is used for dialogue name
> ** Have to wrap text in address tag as there is no markdown equivalent

## Further

The demo uses additional CSS to style the page-look:

```css
body {
  background-color: #eee;
  padding: 2rem 0;
}
article {
  background-color: white;
  border-radius: 4px;
  box-shadow: 0 2px 4px 0 hsla(198, 45%, 10%, .12);
  padding: .5in 0;
}
@media print {
  body {
    padding: 0;
  }
  article {
    box-shadow: none;
    padding: 0;
  }
}
```
