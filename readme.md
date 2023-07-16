Spotify black background ke uppar m chote containers h jo grey color ke h 
so the black div : doesn't contain overflow -> the div inside the container is overflow ! 
<!-- observe spotify website carefully !  -->
# basic theme of how spotify cards/ div are placed  FOr my refernce :)
<div style=" display: flex; ">
  <div style="background-color: green; padding-right: 10px;">first
    <div style="background-color: aqua;">hello </div>
  </div>
   <div style="background-color: blue; padding-left: 10px;">second</div>

</div>
---------------

sometimes we need to make our height of the div == constant and after that only our 
`overflow: auto;` gonna work ! 
------------------------------
