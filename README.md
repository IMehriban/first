<!DOCTYPE html>
<html>
<head>
	<title>Input</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="../assets/css/main.css">
</head>
<body>
	<form action="handle.php" method="get">
		<fieldset>
			<legend>INFORMATION</legend>
		<label>Name:</label> <input type="text" name="name" placeholder="Godek" required>
		<label>Lastname:</label> <input type="text" name="lname" placeholder="Godekow">
		<label>Email:</label> <input type="mail" name="email" placeholder="example@gmail.com" required>
		<label>Password:</label> <input type="password" name="pass" placeholder="min 8 characters" required>
		</fieldset>
		<fieldset>
			<legend>CONNECT</legend>
			<p><input type="radio" name="connect"> Instagram </p>
			<p><input type="radio" name="connect"> Facebook </p>
			<p><input type="radio" name="connect"> Whatsapp </p>
			<p><input type="radio" name="connect"> X </p>
		</fieldset>
		<fieldset>
			<legend>RECOMMENDED BY</legend>
			<select>
				<option default>---SELECT---</option>
				<option>Friends</option>
				<option>Google</option>
				<option>IMO</option>
				<option>LINK</option>
				<option>Other</option>
			</select>
		</fieldset>
		<fieldset>
			<legend>What u prefer?</legend>
			<p><input type="checkbox"> PIZZA</p>
			<p><input type="checkbox"> SALAD</p>
			<p><input type="checkbox"> HAMBURGER</p>
			<p><input type="checkbox"> FITCI</p>
		</fieldset>
		<p align="right"><input type="submit" value="SUBMIT" class="btn"></p>
	</form>
</body>
</html>
