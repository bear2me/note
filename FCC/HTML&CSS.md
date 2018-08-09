It is considered best practice to set a for attribute on the label element, with a value that matches the value of the id attribute of the input element. This allows assistive technologies to create a linked relationship between the label and the child input element. For example:

```html
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
```



Note that it is a good practice to end inline style declarations with a ';' .
padding margin 上右下左 顺时针