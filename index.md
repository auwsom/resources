- Markdown does have collapsable sections, even nested, and uses tag syntax needing ends which breaks easy additions.
  - Two spaces does indent in Markdown, so must need to render collapsing/folding with: 
      - html? 
       - in jekyll?
       - 
<details><summary>Hello</summary><blockquote>
  <details><summary>World</summary><blockquote>
    :smile:
  </blockquote></details>
</blockquote></details>

<details><summary>Hello</summary>text1
  <details><summary>World</summary>text2<blockquote>
    :smile:
  </details>
</blockquote></details>
