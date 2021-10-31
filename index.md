- Markdown does have collapsable sections, even nested, and uses tag syntax needing ends which breaks easy additions.
  - Two spaces does indent in Markdown, but not one. 
    - Not collapsible, use below.
  - need to have script to interpret regular indent structure, and add tags. 
    - easy enough for all nested, but need algo to close when returning.. add end tags appropriately

# Now using LittleOutliner for realtime editablity

##Two spaces without dash or asterisk:
adfvadfv
  adfvadfv
    svadfv
  dfvbadfb
       
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

##Html for collapsible button:

 <button type="button" class="collapsible">Open Collapsible</button>
<div class="content">
  <p>Lorem ipsum...</p>
</div> 
