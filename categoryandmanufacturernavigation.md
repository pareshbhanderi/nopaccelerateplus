---
layout: default
title: Category and Manufacturer Navigation not working
---
<div class="backtoprevpage">
  <button id="backButton">Go Back</button>
</div>
<div class="page-title">
  <h2>Category and Manufacturer Navigation not working</h2>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>Question</span>
    </h3>
  </div>
  <div class="section-content">
    <ul class="subinfo-badges">
      <li>Category and Manufacturer Navigation are not working on our store.</li>
    </ul>
  </div>
</div> 
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>Cause of the Problem</span>
    </h3>
  </div>
  <div class="section-content">
    <ul class="subinfo-badges">
        <li>The "currentCategoryId" is the parameter passed to invoke the CategoryNavigation ViewComponent and is always 0 with nopAccelerate Plus because the controller name is not same as ‘catalog’ since it is overwritten by the nopAccelerate Plus plugin.
        </li>
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
        <li>You can change the Controller Name in _ColumnsTwo.cshtml page of NopCommerce,When you are using NopAccelerate Catalog Plugin</li>
        <li>Replace catalog Controller with NopAcceleratePlusWebCatalog in .cshtml to Load CategoryNavigation & Manufacturer Navigation.
        </li>
      </ul>
  </div>
</div>
