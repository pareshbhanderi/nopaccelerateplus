---
layout: default
title: How to Delete Indexed data
---
<div class="backtoprevpage">
  <button id="backButton">Go Back</button>
</div>
<div class="page-title">
  <h2>How to Delete Indexed data</h2>
</div>
<div class="sub-section">
  <ul class="info-badges">
    <li>
      <div class="subinfo-title">
        <p>If you want to delete data from the Solr Index then you just need to simply run a single query in browser.</p>
      </div>
      <div class="subinfo-content">
        <ul class="subinfo-badges">
          <li>
            <p>http://&lt;hostname&gt;:&lt;port&gt;/&lt;solr-app-name&gt;/&lt;core-name&gt;update?stream.body=&lt;delete&gt;&lt;query&gt;*:*&lt;/query&gt;&lt;/delete&gt;&amp;commit=true</p>
          </li>
          <li>
            <p>Let us see an example</p>
          </li>
          <li>
            <p>Suppose, I have a core with name <strong>"Solr_sample"</strong> and my solr server is running on <strong>port 8983</strong>, then the query will be</p>
          </li>
          <li>
            <p>http://localhost:8983/solr/Solr_sample <strong>/update?stream.body=&lt;delete&gt;&lt;query&gt;*:*&lt;/query&gt;&lt;/delete&gt;&amp;commit=true</strong></p>
            <div class="product-img">
              <img src="/assets/images/erase_data.png" alt="erase_data" />
            </div>
          </li>
        </ul>
      </div>
    </li>
  </ul>
</div>