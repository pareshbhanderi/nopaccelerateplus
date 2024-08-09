---
layout: default
title: TimeOut Expiration Error on Plugin installation
---
<div class="backtoprevpage">
  <button id="backButton">Go Back</button>
</div>
<div class="page-title">
  <h2>TimeOut Expiration Error on Plugin installation</h2>
</div>
<div class="sub-section">
  <div class="sub-title">
    <h3>
      <span>Question</span>
    </h3>
  </div>
  <div class="section-content">
    <ul class="subinfo-badges">
      <li>I am getting below Error while plugin installation</li>
      <li>Timeout expired. The timeout period elapsed prior to completion of the operation or the server is not responding</li>
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
      <li>This problem is caused because you have bunch of record & while Creating our Incremental_Table data, It throws the timeout Issue while executing the Stored procedure 'NopAcc_Plus_ManageIncrementalSolrProductTable'</li>
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
      <li>You need to remove below line of code from Plugin > NopAcceleratePlus.Search > SqlScript > Sp_SolrInstall.sql 'EXEC NopAcc_Plus_ManageIncrementalSolrProductTable'</li>
      <li>Excute this Line of Code on Sql server 'EXEC NopAcc_Plus_ManageIncrementalSolrProductTable'</li>
      <li>After successfully execution of sp, Install the plugin again.</li>
    </ul>
  </div>
</div>
