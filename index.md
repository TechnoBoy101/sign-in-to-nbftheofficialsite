<html>
<head>
	<title>Sign-in</title>
</head>
<body>
	<input type="Username" name="userName" id="userName" class="userName" placeholder="Username: ">
	<p id="incorrect" style="display: none;">Incorrect Username</p>
	<button onclick="signin()">Sign-in</button>
</body>
<script type="text/javascript">
  function signin()
  {
    let username = document.getElementById('userName').value;

    if (username == '1000Infinity') 
    	{
    		window.location.replace("https://www.google.com/url?q=https%3A%2F%2Fsites.google.com%2Fview%2F1000infinity%2Fhome&sa=D&sntz=1&usg=AFQjCNGWpjMoec0IZzfKixHg3tPTwBnrLw");
    	} 
    else if (username == 'InvictusAbhi')
    {
    	window.location.replace("https://www.google.com/url?q=https%3A%2F%2Fsites.google.com%2Fview%2Finvictusabhi%2Fhome&sa=D&sntz=1&usg=AFQjCNGPchy2hIB2IFKfwPbwyVZqmJdxVw");
    }
    else if (username == 'NBFMaster101')
    {
    	window.location.replace("https://www.google.com/url?q=https%3A%2F%2Fsites.google.com%2Fview%2Fnbfmaster101%2Fhome&sa=D&sntz=1&usg=AFQjCNHp0u0QGDJ1fyx19C9V-fiGg_VxQw");
    }
    else if (username == 'InvictusSK')
    {
    	window.location.replace("https://www.google.com/url?q=https%3A%2F%2Fsites.google.com%2Fview%2Finvictussk%2Fhome&sa=D&sntz=1&usg=AFQjCNFqGWMHX3zayHdOthIKd4Cq2DWM0Q");
    }
    else if (username == 'Avalanche0609')
    {
    	window.location.replace("https://www.google.com/url?q=https%3A%2F%2Fsites.google.com%2Fview%2Favalanche0609%2Fhome&sa=D&sntz=1&usg=AFQjCNGLrKVuEe8Eleji6qc51pSwPOz4OA");
    }
    else
    {
    	document.getElementById('incorrect').style.display = 'block';
    }
  }
</script>
</html>
