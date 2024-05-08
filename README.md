# calculator
<!DOCTYPE html> 
<html> 
<head> 
	<title>HTML Calculator</title> 
    </head>
	<style> 
		table { 
			border: 1px solid black; 
			margin-left: auto; 
			margin-right: auto; 
		} 
		
		input[type="button"] { 
			width: 100%; 
			padding: 20px 40px; 
			background-color: red; 
			color:blue; 
			font-size: 24px; 
			font-weight: bold; 
			border: none; 
			border-radius: 5px; 
		} 
		input[type="text"] { 
			padding: 20px 30px; 
			font-size: 24px; 
			font-weight: bold; 
			border: none; 
			border-radius: 6px; 
			border: 3px solid yellow; 
		} 
	</style> 
<body> 
	<table id="calcu"> 
		<tr> 
			<td colspan="3"> 
				<input type="text" id="result"> 
			</td> 
			<td><input type="button" value="c"></td> 
		</tr> 
		<tr> 
			<td><input type="button" value="1"></td> 
			<td><input type="button" value="2"></td> 
			<td><input type="button" value="3"></td> 
			<td><input type="button" value="/"></td> 
		</tr> 
		<tr> 
			<td><input type="button" value="4"></td> 
			<td><input type="button" value="5"></td> 
			<td><input type="button" value="6"></td> 
			<td><input type="button" value="*"></td> 
		</tr> 
		<tr> 
			<td><input type="button" value="7"></td> 
			<td><input type="button" value="8"></td> 
			<td><input type="button" value="9"></td> 
			<td><input type="button" value="-"></td> 
		</tr> 
		<tr> 
			<td><input type="button" value="0"></td> 
			<td><input type="button" value="."></td> 
			<td><input type="button" value="="></td> 
			<td><input type="button" value="+"></td> 
		</tr> 
	</table> 
</body> 
</html> 
