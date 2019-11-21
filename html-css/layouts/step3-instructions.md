The Split Layout is designed to position items horizontally, with one item filling the available horizontal space.

## Task: Make a simplified page header where the "nav" fills the available horizontal space.

1) <strong>Copy code into the index.html file.</strong>

Click the <strong>Copy to Editor</strong> button below to add code in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;header&gt;
  &lt;div&gt;
    Align left.
  &lt;/div&gt;
  &lt;div&gt;
    This element should fill the remaining space between the left and right elements.
  &lt;/div&gt;
  &lt;div&gt;
    Align right.
  &lt;/div&gt;
&lt;/header&gt;
</pre>

2) Add `pf-l-split` to the parent container. 

<strong>Hint: </strong> Add it to `<header>`

3) Add the class `pf-l-split__item` to all of the children inside of the parent container. There are three children.

4) Add `pf-m-fill` to the split item in the middle. This will allow the page nav to fill the available horizontal space in the nav.
