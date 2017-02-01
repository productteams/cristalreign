---
layout: page
title:  "Compare"
date:   2016-09-04 13:46:40
permalink: /plan-comparison/
---
<div align="center">

  <strong>Which plan is right for you?</strong><br>
  <p>We are always here ( blue button at bottom right)<br> 
  to help you choose which plan is best for you. </p>
  Click the image below to see full pass details<br>
  <div>
<img id="myImg" src="http://i.imgur.com/0DwrM8K.png" alt="Ntahoe WeekPass" width="150" height="100">
<!-- The Modal -->
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>
</div>

<script>
// Get the modal
var modal = document.getElementById('myModal');

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById('myImg');
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
    modal.style.display = "none";
}
</script>

  
  <br>
  <table id="customers">
  <tr>
