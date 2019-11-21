The Grid Layout is based on CSS Grid’s two-dimensional system of columns and rows. This layout styles the parent element and its children to achieve responsive column and row spans as well as gutters.

## Task: Layout form components using grid.

1) <strong>Copy code into the index.html file.</strong>

Click the <strong>Copy to Editor</strong> button below to add code in the `index.html` file.

<pre class="file" data-filename="index.html" data-target="replace">
&lt;div class=&quot;pf-c-card&quot;&gt;
  &lt;div class=&quot;pf-c-card__body&quot;&gt;
    &lt;form class=&quot;pf-c-form&quot;&gt;
      &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;Name&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; required&gt;
      &lt;/div&gt;
      &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;Email&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; required&gt;
      &lt;/div&gt;
      &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;Phone number&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; placeholder=&quot;555-555-5555&quot;&gt;
      &lt;/div&gt;
      &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;Street Address&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; placeholder=&quot;123 A Street&quot;&gt;
      &lt;/div&gt;
      &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;State&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; placeholder=&quot;MA&quot;&gt;
      &lt;/div&gt;
      &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;Zip Code&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; placeholder=&quot;12345&quot;&gt;
      &lt;/div&gt;
        &lt;div class=&quot;pf-c-form__group&quot;&gt;
        &lt;label class=&quot;pf-c-form__label&quot;&gt;Country&lt;/label&gt;
        &lt;input class=&quot;pf-c-form-control&quot; placeholder=&quot;United States&quot;&gt;
      &lt;/div&gt;
    &lt;/form&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>

2) Add `pf-l-grid` next to the `pf-c-form` class.

3) For every `pf-c-form__group` class add `pf-l-grid__item` next to it so that it becomes a grid item.

4) Change the widths of `pf-l-grid__item`. To the first two Form Groups add `pf-m-6-col` next to `pf-l-grid__item`. For the last three Form Groups add `pf-m-4-col` next to `pf-l-grid__item`.
