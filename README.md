<h3> </h3>

<p>
<ul>
<li> Add BengaliEditText.jar to buildpath and put phonetic.xml and solaimanlipinormal.ttf in assets folder </li>
<li> <pre> In xml, instead of EditText, it will be  "<androidbangladesh.BengaliEditText />" </pre> <li>
<li> From java just do, "BengaliEditText bet = (BengaliEditText)findViewById(R.id.edit_text_id);" </li>
<li> bet.getInputText() returns the english text </li>
</ul>
</p>
