# HTML
## Miscellaneous
### Space
```html
&nbsp;
```
半角的不断行的空白格（推荐使用）。这是我们使用最多的空格，也就是按下space键产生的空格。在HTML中，如果你用空格键产生此空格，空格是不会累加的（只算1个）。要使用html实体表示才可累加。该空格占据宽度受字体影响明显而强烈。在inline-block布局中会搞些小破坏，在两端对齐布局中又是不可少的元素。

```html
&ensp;
```
半角的空格。此空格有个相当稳健的特性，就是其占据的宽度正好是1/2个中文宽度，而且基本上不受字体影响。

```html
&emsp;
```
全角的空格。此空格也有个相当稳健的特性，就是其占据的宽度正好是1个中文宽度，而且基本上不受字体影响。
## Semantic
### &lt;section&gt; vs &lt;div&gt;
`<section> tag has a semantic meaning unlike <div>. semantic tags describe their meaning both to the developer and the browser. Basically, the <section> tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.`
  
`On the other hand, <div> has no meaning, typically used for grouping elements and styling them via CSS.If you just need to group content together for styling purposes you should use a <div> element rather than a <section>.`
### &lt;section&gt; vs &lt;article&gt;
`The <article> tag should contain a piece of self-contained content that could be distributed outside the context of the page. This includes things like news articles, blog posts, or user comments.`

`The <section> element is used to represent a group of related content. This is similar to the purpose of an <article> element with the main difference being that the content within a <section> element doesn’t necessarily need to make sense out of the context of the page.`
## Template
## ARIA
