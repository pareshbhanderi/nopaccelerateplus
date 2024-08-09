---
layout: default
title: Responsive filter not working with noptemplate theme
---
<div class="backtoprevpage">
  <button id="backButton">Go Back</button>
</div>
<div class="page-title">
  <h2>Responsive filter not working with noptemplate theme</h2>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>Question</span>
    </h3>
  </div>
  <div class="section-content">
    <ul class="subinfo-badges">
      <li>Responsive filters of nopAccelerate plus is not working with nop-template themes ?</li>
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
      <li>If responsive not working with nopTemplate theme,please need to do some CSS changes please check the below CSS changes</li>
    </ul>
  </div>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>CSS Changes => Themes</span>
    </h3>
  </div>
  <div class="section-content">
    <p><strong>In case you are using one of the below themes of nop-template, then you need to apply CSS changes mentioned in section 1.</strong></p>
    <ul class="subinfo-badges">
      <li>Lighthouse</li>
      <li>Alfresco</li>
      <li>Jewelry</li>
      <li>NeoFashion</li>
      <li>Beauty</li>
      <li>Fashion</li>
      <li>Electronics</li>
      <li>Shop All</li>
    </ul>
  </div>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>UI Changes => Themes => Section 1</span>
    </h3>
  </div>
  <div class="section-content">
    <p><strong>Open the "nopaccelerate-style.min.css" file and apply below changes</strong></p>
    <ul class="subinfo-badges">
      <li>Search for "max-width:1000px" property and instead set "max-width:767px".</li>
      <li>Search for "min-width:1001px" property and instead set "min-width:768px".</li>
    </ul>
    <p><strong>Open the "nopaccelerate-style.rtl.min.css" file and apply below changes</strong></p>
    <ul class="subinfo-badges">
      <li>Search for "max-width:1000px" property and instead set "max-width:767px".</li>
      <li>Search for "min-width:1001px" property and instead set "min-width:768px".</li>
    </ul>
  </div>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>UI Changes => Themes => Section 2</span>
    </h3>
  </div>
  <div class="section-content">
    <p><strong>In case you are not using any of the above mentioned themes of nop-template, then you need to apply CSS changes mentioned in section 2.</strong></p>
    <p><strong>Open the "nopaccelerate-style.min.css" file and apply below changes</strong></p>
    <ul class="subinfo-badges">
      <li>Search for "max-width:1000px" property and instead set "max-width:1024px".</li>
      <li>Search for "min-width:1001px" property and instead set "min-width:1025px".</li>
    </ul>
    <p><strong>Open the "nopaccelerate-style.rtl.min.css" file and apply below changes</strong></p>
    <ul class="subinfo-badges">
      <li>Search for "max-width:1000px" property and instead set "max-width:1024px".</li>
      <li>Search for "min-width:1001px" property and instead set "min-width:1025px".</li>
    </ul>
  </div>
</div>