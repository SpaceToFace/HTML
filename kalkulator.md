<!DOCTYPE html>
<html>
	<head>
		<meta charset=UTF-8>
	</head>
	<style>
		input {
			width: 150px;
		
		}
	</style>
	<body>
		<form oninput="x.value = parseInt(a.value) * parseInt(b.value) * (1+ parseFloat(c.value))">
			<table align=center width=30% height=300px border=0 cellspacing=10 bgcolor=#fff6db>
				<tr height=20px>
					<td><b>INVOICE</b></td>
				</tr>
				<tr>
					<td>
						<table align=cenetr height=100% width=100% border=0>
							<tr>
								<td align=center width=40%>
									<p>
										Numbers of hours:
									</p>
								</td>
								<td>
									<p>
										<input type="number" name="a" min="0" value=0> 
									</p>
								</td>
							</tr>
						</table>
					</td>
				</tr>
				<tr>
					<td>
						<table align=cenetr height=100% width=100% border=0>
							<tr>
								<td align=right width=37%>
									<p>
										Rate:
									</p>
								</td>
								<td width=6px></td>
								<td>
									<p>
										<input type="number" name="b" min="0" value=0 >
										&nbsp;&nbsp;(&pound's)
									</p>
								</td>
							</tr>
						</table>
					</td>
				</tr>
				<tr>
					<td>
						<table align=cenetr height=100% width=100% border=0>
							<tr>
								<td align=right width=37%>
									<p>
										VAT:
									</p>
								</td>
								<td width=6px></td>
								<td>
									<p>
										<input type="number" name="c" step="0.1" min="0" max="23" value=0>
									</p>
								</td>
							</tr>
						</table>
					</td>
				</tr>
				<tr>
					<td>
						<table align=cenetr height=100% width=100% border=0>
							<tr>
								<td align=right width=37%>
									<p>
										<b>TOTAL:</b>
									</p>
								</td>
								<td width=6px></td>
								<td>
									&pound;<output name="x">--</output>
								</td>
							</tr>
						</table>
					</td>
				</tr>
			</table>
		</form>
	</body>
</html>
