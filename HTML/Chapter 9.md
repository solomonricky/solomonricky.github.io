# Chapter 09's Note

### Form Tag: </br>
- `<form></form>` : Every form tag must inside of `<form></form>` tag.</br>
- `<input></input>` : Single line text column.</br>
- `<textarea></textarea>` : Multiple line text column.</br>
- `<select></select>` : Selection arcording to `<option></option>` which given.</br>
<hr/>

#### `<form></form>`'s tags
- name : `<form name="myForm"></form>` is specifies the name of the form.
- method : `<form method="post/get"></form>` is specifies how to send form-data.
- action : `<form action="index.php"></form>` is specifies where to send the form-data when a form is submitted.
- target : `<form target="_blank"></form>` is specifies the target for where to submit the form.
- enctype : `<form enctype="path/name"></form>` is specifies how the form-data should be encoded when submitting it to the server (only for method="post").

#### `<input type="method" />`'s tags
- text : Single line text column.
  - value : `<input type="text" value="Default"/>` is the default value. It will show at the column.
  - size : `<input type="text" size="n"/>` is the length of the column.
  - maxlength : `<input type="text" maxlength="n"/>` is the max length of the input text.
- password : Password column.
  - value : `<input type="password" value="Default"/>` is the default value. It will show at the column.
  - size : `<input type="password" size="n"/>` is the length of the column.
  - maxlength : `<input type="password" maxlength="n"/>` is the max length of the input password.
- radio : Only one radio button in a group can be selected at the same time.
  - `<input type="radio" name="Group" value="Selection 1" checked />Selection 1`
  - There is only one selection in the same `Group`.
  - The function of `checked` is make default selection to the selection which insert `checked`.
  - **DON'T FORGET YOUR `NAME`, IT'S VERY IMPORTANT!**
- checkbox : Let a user select one or more options of a limited number of choices.
  - `<input type="checkbox" name="Group" value="Selection 1" checked />Selection 1`
  - There can have many selection in the same `Group`.
  - The function of `checked` is make default selection to the selection which insert `checked`.
  - **DON'T FORGET YOUR `NAME`, IT'S VERY IMPORTANT!**
- button/submit/reset : Button.
- file : Upload file.

#### `<textarea rows="n" cols="n" value="">Default index.</textarea>`'s tags
- `textarea` : User can insert multiple rows.

#### `<select></select>`'s tags
- `<select multiple>` : User can choose more than one options.
- `<select size="n">` : Default the value of options will be shown.
- `<option>Option 1</option>`'s tag must be 
- inside of `select`'s tag.
