</select>"><!DOCTY<map name="">
	<area shape="" href="" coords="" alt="">
</map>PE html>
<html lang="en"><strong><strong><strong><strong><strong></strong></strong></strong></strong></strong>
 <head>
  <meta charset="UTF-8">
  <meta name="Generator" content="EditPlus®">
  <meta name="Author" content="">
  <meta name="Keywords" content="">
  <meta name="Description" content="">
  <title>Document</title>
  <script>
	function chng()
	{
		if(document.forms[0].city.value=="00")
		{
			document.forms[0].txt.value = "none";
			document.forms[0].btn.value = "none";
		}
		if(document.forms[0].city.value=="Bangalore")
		{
			document.forms[0].txt.value = "Bangalore";
			document.forms[0].btn.value = "Bangalore";
		}
		if(document.forms[0].city.value=="Chennai")
		{
			document.forms[0].txt.value = "Chennai";
			document.forms[0].btn.value = "Chennai";
		}
		if(document.forms[0].city.value=="Hydrabed")
		{
			document.forms[0].txt.value = "Hydrabed";
			document.forms[0].btn.value = "Hydrabed";
		}
		if(document.forms[0].city.value=="Pune")
		{
			document.forms[0].txt.value = "Pune";
			document.forms[0].btn.value = "Pune";
		}
		if(document.forms[0].city.value=="Noida")
		{
			document.forms[0].txt.value = "Noida";
			document.forms[0].btn.value = "Noida";
		}
	}
  </script>
 </head>
 <body>
 <form>
  <table>
  	<tr>
		<td>city</td>
	</tr>
  	<tr>
		<td>
			<select name="city" id="city" value="none" onchange="chng();">
				<option value="00">---Select---</option>
				<option value="Bangalore">Bangalore</option>
				<option value="Chennai">Chennai</option>
				<option value="Hydrabed">Hydrabed</option>
				<option value="Noida">Noida</option>
				<option value="Pune">Pune</option>
			</select>
		</td>
		<td><input type="text" name="txt" id="txt" value="none" readonly></td>
		<td><input type="button" name="btn" id="btn" value="none"></td>
	</tr>
  </table>
 </form>
 </body>
