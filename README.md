<div id=":1b3" class="ii gt m14b3b1af6261bdc3 adP adO"><div id=":1b4" class="a3s" style="overflow: hidden;"><div dir="ltr"><div class="adM"><br></div><h3>Print Format Help For ERPNext<br></h3>
<hr>
<h4>Introduction</h4>
<p>Print Formats are rendered on the server side using the Jinja Templating Language. All forms have access to the <code>doc</code> object which contains information about the document that is being formatted. You can also access common utilities via the <code>frappe</code> module.</p>
<p>For styling, the Boostrap CSS framework is provided and you can enjoy the full range of classes.</p>
<hr>
<h4>References</h4>
<ol><li><a href="http://jinja.pocoo.org/docs/templates/" target="_blank">Jinja Tempalting Language: Reference</a></li><li><a href="http://getbootstrap.com" target="_blank">Bootstrap CSS Framework</a></li></ol>
<hr><h4>Other Notes:</h4><p>1) Fetching document object</p><pre><code>{{ doc.customer_name }}</code></pre><p>2) Date format</p><p>{{ doc.get_formatted("po_date") or ''}}<br></p><p>3) Currency Formate <br></p><p>{{ doc.get_formatted("date") }}</p><p>4) Avoiding None in Print Format:<br></p><p>Fetching Batch number if ordered item has batch. <br></p><p>Write if condition, otherwise it will print None<br></p><p>{%- if row.batch_no -%}<br>&lt;b&gt;Batch No: &lt;/b&gt;{{ row.batch_no or '' }} &lt;br&gt;<br>{%- endif -%}<br></p><p><br></p><p>If
 you find any bug in this repository or want any help for customizing 
ERPNext, Customise print formate you can contact me or drop email.</p><div> <b>Sambhaji Kolate</b><br> <span>Software Developer</span>, <span>sbkolate.com</span> </div><div style="color:rgb(141,141,141);font-size:13px;padding:5px 0px"> <span style="display:inline-block"><span style="color:rgb(69,102,142)">Mobile: </span><a href="tel:9850015051" style="color:rgb(141,141,141);text-decoration:none" target="_blank">9850015051</a></span>  | <span style="display:inline-block"><span style="color:rgb(69,102,142)">Email:</span><a href="mailto:kolate.sambhaji@gmail.com" target="_blank">kolate.sambhaji@gmail.<wbr>com</a></span><br><br></div><div style="color:rgb(141,141,141);font-size:13px;padding:5px 0px"><br>
<hr>Thanks to <a href="http://erpnext.com/" target="_blank">ERPNext</a><a> Team</a> for Great Product</div><div class="yj6qo"></div><div class="adL" style="color:rgb(141,141,141);font-size:13px;padding:5px 0px"><br><br><br><br></div></div><div class="adL">
</div></div></div>
