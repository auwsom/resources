- Markdown does have collapsable sections, even nested, and uses tag syntax needing ends which breaks easy additions.
  - Two spaces does indent in Markdown, but not one. 
    - Not collapsible, use below.
  - need to have script to interpret regular indent structure, and add tags. 
    - easy enough for all nested, but need algo to close when returning.. add end tags appropriately
    - 
       
<details><summary>
Hello
</summary><blockquote>
  
<details><summary>
  World
</summary><blockquote>
  
<details><summary>
    :smile:
</summary><blockquote>
</blockquote></details>
  
</blockquote></details>
  
<details><summary>
  World2
</summary><blockquote>
</blockquote></details>
  
</blockquote></details>
  
<details><summary>
Hello2
</summary><blockquote>
</blockquote></details>


<div id="section1">
  <h1>Section 1</h1>
  <p>Section 1 content</p>
  <div id="section1-1">
    <h2>Section1-1</h2>
    <p>section 1-1 content</p>
  </div>
    <div id="section1-2">
    <h2>Section1-2</h2>
    <p>section 1-2 content</p>
  </div>
</div>
