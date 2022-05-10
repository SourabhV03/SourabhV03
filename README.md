<html>
<head>
<title> REGISTER FORM </title>
 <link rel="stylesheet" href="registration.css">
</head>
<body>
<div class="box-form">
	<div class="center">
	<h1>Please Register</h1>
	</div>
<form>
	<table>
			<tr>
				<td>
					First Name :
				</td>
				<td>
				
					<input type="text" placeholder="First Name" name="First_name" required>
				</td>
			</tr>
			<tr>
				<td>
					Middle Name :
				</td>
				<td>
				
					<input type="text" placeholder="Middle Name" name="Middle_name" required>
				</td>
			</tr>
			<tr>
				<td>
					Last Name :
				</td>
				<td>
				
					<input type="text" placeholder="Last Name" name="Last_name" required>
				</td>
			</tr>
			<tr>
				<td>
						Password:
				</td>
				<td>
					
					<input type="password" placeholder="Enter Password" name="psw" required>
				</td>
			</tr>
			<tr>
				<td>
					Gender :
				</td>
				<td>
				
					<input type="radio"  name="Gender" value="M" required>Male
					<input type="radio"  name="Gender" value="F" required>Female 
				</td>
			</tr>
			<tr>
				<td>
					Email :
				</td>
				<td>
						 <label for="email"><i class="fa fa-envelope"></i></label>
						 <input type="email" id="email" class="cm-input" placeholder="Enter your email adress" required>
				</td>
			</tr>
			<tr>
				<td>
					Mobile no :
				</td>
				<td>
					<select name="phoneCode">
						<option value="+91">+91</option>
					</select>
						<input type="phone" placeholder="98754*****"name="phone" onkeypress="return onlyNumberKey (event)" required>
				</td>
			</tr>
			<tr>
				<td>
				
					<button type="submit" class="submit  gr-bg">submit</button>
				</td>
			</tr>
		</table>
</form>
</body>
</html>		
		
