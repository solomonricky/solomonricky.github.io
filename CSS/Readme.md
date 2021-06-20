# CSS(Cascading Style Sheets) Note

#### Type of CSS: <br/>
- Inline CSS : Must be specified on every HTML tag.
  - `<div style="color:red;"> Hello World!</div>`
- Internal CSS : Specified in the `<head>` section. It affects all the elements in the body section.
  - `<style type="text/css">`<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`div{color:red;}`<br/> `</style>`
- External CSS : Create a .css file and use it in our HTML page as per our requirement. No need to rewrite the CSS style again and again in a complete body of HTML.
  - `<link ref="stylesheet" type="text/css" href="path" />`
<hr/>

#### CSS Selector: <br/>
- Element Selector
- ID Selector
- Class Selector
- Universal Selector
- Grouping Selector
<hr/>

#### Font: <br/>
- font-family
- font-size
- font-weight
  - normal
  - lighter
  - **bold**
  - bolder
- font-style
  - normal
  - italic
  - oblique
- color
- comment
  - `/* This is a comment, */`
<hr/>

#### Text-Style
- `text-indent` : Specifies the indentation of the first line in a text-block. 首行缩进
- `text-align` : Specifies the horizontal alignment of text in an element. 水平对齐
  - left
  - center
  - right 
- `text-decoration` : Specifies the decoration added to text, and is a shorthand property. 文本修饰
  - none(default)
  - underline
  - line-through
  - overline
- `text transform` : Controls the capitalization of text. 大小写转换
  - none
  - lowercase
  - uppercase
  - capitalize
- `line-height` : Line height. 行高
- `letter-spacing, word-spacing` : Spacing between letter or word. 字母间距,词间距
