<!DOCTYPE html>
<html>
	<head>
		<meta charset=UTF-8>
	</head>
	
	<body>
		<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
		<form  action="http://postman-echo.com/post" method="POST">
			<table align=center width=20% height=650 border=0 bgcolor="black" cellspacing=5>
				<tr height=70px>
					<td align=center>
						<font face="Roboto" color=#20b8c6 size=7>INQUIRES</font>
					</td>
				</tr>
				<tr>
					<td>
						<table bgcolor=#20b8c6 align=center width=100% height=500 border=0 bgcolor="black" cellspacing=0>
							<tr height=25px>
								<td></td>
							</tr>
							<tr height=30px>
								<td align=center>
									<font color="white" face=Roboto>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris elementum nisi odio.</font>
								</td>
							</tr>
							<tr height=5%>
								<td>
									<table width=100% border=0 height=100% align=center bgcolor=#20b8c6 colspan=2>
										<tr>
											<td width=50%>
												<p align=center>
													<input 
														type="text"
														name="Imie"
														placeholder="Wpisz Imie"
														size=38>
												</p>
												<p align=center>
													<input
														type="tel"
														name="telefon"
														placeholder="Wpisz numer telefonu"
														size=38>
												</p>
											</td>
											<td>
												<p align=center>
													<input 
													type="text"
													name="Nazwisko"
													placeholder="Wpisz Nazwisko"
													size=38>
												</p>
												<p align=center>
													<input
														type="email"
														name="Mail"
														placeholder="Wpisz mail"
														size=38>
												</p>
											</td>
										</tr>
									</table>
								</td>
							</tr>
							<tr>
								<td height=5px>
									<table width=100% height=100% border=0>
										<tr>
											<td>
												<pre>
   <select name="jezyk" multiple size=1>
   <option>Język polski</option>
   <option>Język angielski</option>
   <option>Język niemicki</option>
   </select>

   <textarea name="dlugi_teskt" rows=10 cols=89></textarea>
												</pre>								
											</td>
										</tr>
									</table>
								</td>
							</tr>
							<tr height=10px>
								<td>
									<table align=center width=100% height=100% border=0>
										<tr>
											<td>
												<pre>
												
										      <input type="submit" value="SEND">
												</pre>
											</td>
										</tr>
									</table>
								</td>
							</tr>
						</table>
					</td>
				</tr>
		</table>
	</body>
</html>
