---
layout: default
title: How Can I search with synonyms ?
---
<div class="backtoprevpage">
  <button id="backButton">Go Back</button>
</div>
<div class="page-title">
  <h2>How Can I search with synonyms ?</h2>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>Question</span>
    </h3>
  </div>
  <div class="section-content">
    <ul class="subinfo-badges">
      <li>I have products with the name "Laptop" and the user write in the textbox "NoteBook" , So I need search result of Laptop.</li>
      <li>How to set this configuration and the Solr and what file should I use?</li>
    </ul>
  </div>
</div> 
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>Solution</span>
    </h3>
  </div>
  <div class="section-content">
    <ul class="subinfo-badges">
      <li>Changes are required in synonyms.txt , you can find this file at C:\solr-6.4.2\server\solr\&lt;YourCoreName&gt;\conf\synonyms.txt</li>
      <li>You just need to add below line in the end of synonyms.txt.</li>
      <li>NoteBook=>Laptop</li>
    </ul>
    <p><strong>[Note:</strong> Make sure you reload core once you make changes in synonyms.txt]</p>
  </div>
</div>
