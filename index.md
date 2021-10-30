- Markdown does have collapsable sections, but not nested, and uses tag syntax needing ends which breaks easy additions.
    - Four spaces does indent in Markdown, so must need to render collapsing/folding with: 
        - html? 
        - in jekyll?


<details>
Heading 1
+   &ensp;<details>Heading1
+       &ensp;<details>Heading2



# Header 1
## Header 23
# A collapsible section with markdown
<details><summary>
Heading 1
</summary>  
+   &ensp;<details><summary>Heading1</summary>sub1
+       &ensp;<details><summary>Heading2</summary>sub2
</details>
</details>
</details>



</summary>
</summary>
## Heading\1
## Heading\1


*&ensp;<details>
+    &ensp;<details>
  <summary>
  <summary>
  Heading 1
  Heading 1
  </summary>
  </summary>
  &ensp;# Heading\2
  &ensp;# Heading\2
  </details>


</details>

+ test
+ test
+ 1
+ 1
  + 2
  + 2


   test
   test
     tab space
     tab space
  </details>

</details>

