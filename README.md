<p align="center">
<img src="https://github.com/user-attachments/assets/5f8cca5c-2a73-489b-a9d9-a803075823a5" alt="HTML5 Logo"/>
</p>

<h1>Make an Email Signature from Scratch</h1>
If you want to try your hand at a bit of HTML in a practical way without having to build a website, an email signature is a great way to start. There are plenty of free tools that you can build a decent email signature like Hubspots: https://www.hubspot.com/email-signature-generator, so doing it yourself is not necessary. It can be a fun way to play with HTML in a way that other people might see without having to worry about hosting a website. 

<h2>See Examples</h2>

![Screenshot 2025-03-30 7 55 44 PM](https://github.com/user-attachments/assets/a7fa3d48-7fe3-44b5-8789-e44e4aefccd6)

![example](https://github.com/user-attachments/assets/aac62d20-5be6-4abd-8d9c-f6522f223d03)

<h3>Instruction</h3>

Open a text file on your computer and save it as index.html. Copy and paste the text from below and paste it into your file, save. Right click on your file from file manager and open in Chrome to see the HTML code run. You can copy and paste this code from the browser and paste it into your email signature area. 

<h3>The Code:</h3>

```HTML
<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>HTML Email Signature</title>
	<style type="text/css">
		body {
			margin: 0;
		}
		table {
			border-spacing: 0;
		}
		td {
			padding: 0;
		}
		img {
			border: 0;
		}
		.wrapper {
      max-width: 600px;
		width: 100%;
      table-layout: fixed;
		}
		.main {
      width: 100%;
      background-color: #fff;
      font-family: Arial, Helvetica, sans-serif;
      color: #282828;
			     text-align: left;
		}

	</style>
</head>
<body>

	<center class="wrapper">

		<table class="main" width="100%">

<!-- PROFILE IMAGE -->
			<tr>
				<td style="padding: 20px 0 8px 10px;">
					<img src="https://i.imgur.com/DjJGaO2.png" alt="Branden Osborne" width="150" style="display: block; outline: none; border: 0; border-radius: 5px;">
				</td>
			</tr>
			
<!-- NAME -->
			<tr>
				<td style="font-size: 22px; line-height: 24px; font-weight: 700; padding: 5px 0 0 12px; text-align: left;">Branden Osborne
				</td>
			</tr>

<!-- TITLE -->
			<tr>
				<td style="font-size: 16px; line-height: 18px; font-weight: 400; text-transform: uppercase; letter-spacing: 2px; padding: 10px 0 0 12px; text-align: left;">IT Professional
				</td>
			</tr>

<!-- EMAIL -->
			<tr>
				<td style="padding: 0;">
					<table width=:100%">
					
						<tr>
							<td style="padding: 8px 0 0 10px;">
								<a href="mailto:brandenosborne14@gmail.com"><img src="https://i.imgur.com/RWBxBA2.png" alt="Email Me"
										width="22" style="border: 0;"></a>
								<a href="mailto:brandenosborne14@gmail.com"
									style="text-decoration: none; color: #282828; font-size: 16px;">brandenosborne14@gmail.com</a>
							</td>
						</tr>

					</table>
				</td>
			</tr>

<!-- WEBSITE -->
			<tr>
				<td style="padding: 0;">
					<table width=:100%">
					
						<tr>
							<td style="padding: 5px 0 0 10px;">
								<a href="https://github.com/brandenoz"><img src="https://i.imgur.com/fg8x3OE.png" alt="Website"
										width="22" style="border: 0;"></a>
								<a href="https://github.com/brandenoz"
									style="text-decoration: none; color: #282828; font-size: 16px;">github.com/brandenoz</a>
							</td>
						</tr>

					</table>
				</td>
			</tr>

<!-- PHONE -->
			<tr>
				<td style="padding: 0;">
					<table width=:100%">
					
						<tr>
							<td style="padding: 8px 0 0 10px;">
								<a href="tel:1-863-529-3014"><img src="https://i.imgur.com/mOO1zRA.png" alt="Call Me"
										width="22" style="border: 0;"></a>
								<a href="tel:1-863-529-3014"
									style="text-decoration: none; color: #282828; font-size: 16px;">1-863-529-3014</a>
							</td>
						</tr>

					</table>
				</td>
			</tr>

<!-- SOCIAL MEDIA -->
			<tr>
				<td style="padding: 0;">
					<table width="100%">
					
						<tr>
							<td style="padding: 14px;">
								<a href="https://www.linkedin.com/in/branden-osborne/" target="_blank"><img src="https://i.imgur.com/UAdZs7z.png" alt="LinkedIn" width="30" style="border: 0;"></a>
								<a href="https://www.goodreads.com/user/show/64632890-branden-osborne" target="_blank"><img src="https://i.imgur.com/9tJCM2K.png" alt="Goodreads" width="30" style="border: 0;"></a>

							</td>
						</tr>

<!-- CALL TO ACTION -->

			<tr>
				<td>
					<a href="https://calendly.com/brandenosborne14/30min" target="_blank" style="text-decoration: underline; padding: 5px 0 0 12px; line-height: 24px; color: #CE0E2D; font-size: 16px; font-weight: 500;">Book Appointment</a>
				</td>
			</tr>
						
					</table>
				</td>
			</tr>

		</table> <!-- End Main Class -->

	</center> <!-- End Wrapper -->

</body>
</html>
```
- To see other projects click here: https://github.com/brandenoz. 
