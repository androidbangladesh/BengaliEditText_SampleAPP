<h3> </h3>

<p>
<ul>
<li> Add BengaliEditText.jar to buildpath and put phonetic.xml and solaimanlipinormal.ttf in assets folder </li>
<li>In xml, instead of <EditText />, it will be  "<androidbangladesh.BengaliEditText &#47;&#62;"</li>
<li> From java just do, "BengaliEditText bet = (BengaliEditText)findViewById(R.id.edit_text_id);" </li>
<li> bet.getInputText() returns the english text </li>
</ul>
</p>
