<h3> </h3>

<p>
<ul>
<li> Add BengaliEditText.jar to buildpath and put phonetic.xml and solaimanlipinormal.ttf in assets folder </li>
<li>In xml, instead of <b> &#60EditText &#47;&#62;</b>, it will be <b> &#60;androidbangladesh.BengaliEditText &#47;&#62;</b></li>
<li> From java just do, "BengaliEditText bet = (BengaliEditText)findViewById(R.id.edit_text_id);" </li>
<li> bet.getInputText(): returns the english text </li>
</ul>
</p>
