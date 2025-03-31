<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>How to send data from an HTML form to email</title>

	<!-- custom css style link -->
	<link rel="stylesheet" href="style.css">
	<!-- font link -->
	<link href="https://googleapis.com/css?famali=Nunito" rel="stylesheet" type="text/css">
</head>

<body>

<!-- contacts section start -->

<section class="contacts">

	<h2 class="heading"><span>Contact</span>Us</h2>	

	<div class="row"> 
		<div class="img">
		   <img src="1.png">	
		</div>
		<form action="register.html https://api.web3forms.com/submit" method="post">
			<input type="hidden" name="access_key" value="d3760a67-b5ff-4b41-a241-393dde56386b">
			<p style="color: white; font-size: 25px; margin-bottom: 40px;">Информация о вас:</p>
			<span>Your name</span>
			<input type="text" name="name" id="" class="box" required placeholder=" Ваше имя.." autocomplete="off">

			<span>Your username</span>
			<input type="text" name="name" id="" class="box" required placeholder="Имя пользователя.." autocomplete="off">

			<span>Your email</span>
			<input type="email" name="email" id="" class="box" required placeholder=" Ваша эл почта.." autocomplete="off">
			<span>Your number</span>
			<input type="number" name="number" id="" class="box" required placeholder="Ваш номер.." autocomplete="off">

			<span>Select cources</span>
			<select name="courses" id="" class="box" required>
				<option value="" disabled selected>Ваш город</option>
				<option value="HTML">HTML</option>
				<option value="CSS">CSS</option>
				<option value="JavaScript">JavaScript</option>
				<option value="PHP">PHP</option>
				<option value="Python">Python</option>
			</select>

			<span>Select gender</span>
			<div class="gender">
				<input type="radio" name="gender" id="male" value="male">
				<label for="male">male</label>

				<input type="radio" name="gender" id="male" value="male">
				<label for="male">female</label>
			</div>

			<input type="submit" value="Отправить информацию" class="btn" name="send" style="height: 30px; width: 170px; border-radius: 7px;">

		</form>

	</div>

</section>

<!-- contacts section end -->

</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title></title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<section style="background-color: black; height: 500px;">
	<form action="register.html" method="post">
		<p style="color: white; margin-left: 670px; font-size:25px">Регестрация</p>
		
		<input type="text" placeholder="login" name="login" style="width: 560px;margin: 1rem 0rem 2rem;border-radius: 0.5rem;padding: 0.8rem; margin-left: 670px">
		<input type="text" placeholder="password" name="pass" style="width: 560px;margin: 1rem 0rem 2rem;border-radius: 0.5rem;padding: 0.8rem; margin-left: 670px">
		<input type="text" placeholder="repeat password" name="repeatpass" style="width: 560px;margin: 1rem 0rem 2rem;border-radius: 0.5rem;padding: 0.8rem; margin-left: 670px">
		<input type="text" placeholder="email" name="email" style="width: 560px;margin: 1rem 0rem 2rem;border-radius: 0.5rem;padding: 0.8rem; margin-left: 670px">
		<div>
		    <input type="submit" value="Send data" class="btn" name="send" style="height: 30px; width: 100px; border-radius: 7px; margin-left: 670px;">Зарегестрироваться</button>
	   </div>

	</form>
   </section>

</body>
</html>
