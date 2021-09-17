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
<hr/>

#### Border
- `border-width:0px;` : The width of border.
- `border-style:none/dashed/solid;` : The border style.
- `border-color:red;` : The border color.
- `border:0px none red;` : The shortcut of border.<br/>
- `border-top/bottom/left/right-width` : Spectific CSS for certain part of border.
<hr/>

#### List-Style-Type
- `ol{list-style-type:lower-roman;}` : Use at `ul` & `ol` element not in `li` element.
- `ul,ol{list-style-type:none;}` : Often use `none` to delete to symbol.
- `ul{list-style-image:url(path);}` : Use image as symbol.
  - Normal will not using `list-style-type` to make the symbol but use `iconfont`.
<hr/>

#### Table
- `table{caption-side:value;}` : Specifies the placement of table. (Value = top / bottom)
- `table{border-collapse: value;}` : Remove the space between border and border. (Value = seperate / collapse)
- `table{border-spacing:0px;}` : Adding spacing between border and border.
<hr/>

#### Image
- `width:100px;` : Determine the width of Image.
- `height:100px;` : Determine the height of Image.
- `border:1px solid black;` : Determine the border of Image.
- `.img1{text-align:value;}` : Image alignment, `text-align` only use at image and text. (Value = left / center / right)
- `.img{vertical-align:value;}` : Image vertical alignment. (Value = top / middle /baseline / bottom)
- `.img1{float:value;}` : Add image beside text. (Value = left / right)
<hr/>

#### Background
- `.bg{background-color:color-value;}` : Set background color.
- `.bgimage{background-image: url(path/name.png);}` : Set background image.
- `.bgrepeat{background-repeat: value;}` : Repeat the background icon. (Value = repeat / repeat-x / repeat-y / no-repeat)
- `.bgposition{background-position: horizontal vertical / keyword;}` : Set background position.
- `.bgatm{background-attachment: value;}` : Spectific the background is fix or scroll. (Value : fixed / scroll)
<hr/>

#### Hyperlink
- `a:link{color:value;}` : When the link have not visited.
- `a:visited{color:value;}` : When the link had been visited.
- `a:hover{color:value;}` : When the mouse cursor on the link. (Can use it individual.)
  - hover can use at any element such as `div:hover` & `img:hover`.
- `a:active{color:value;}` : When opening the link.
- Must be link -> visited -> hover -> active

##### Mouse cursor
- `.default{cursor:value;}` : Normal we just use (Value = default / pointer / text).
- `.customize{cursor:url(path/name,default;)`Customize our cursor ourself with **".cur"**.

##### Float and Clear
- `float:left` : Set floating format. (Value = left / right / none)
- `clear:both` : Clear floating format. Usually we using both. (Value = left / right / both)

##### Position
- `position:fixed` : When scroll the website it the content will still at the fixed position. Must pair with top / left / bottom / left. #浏览器角度
- `position:relative` : Change the layout from the initial code. Must pair with top / left / bottom / left.
- `position:absolute` : Change the layout from the browser. Must pair with top / left / bottom / left.
- `position:static` : Default. Usually use in Javascripts.