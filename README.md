# Exp-1-To-create-a-web-Portfolio-CV-using-HTML-CSS

## AIM:

To create a portfolio using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document.

2. Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3. Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4. Add a header section to display your name or the title of your portfolio.

5. Add images or media to enhance your portfolio. You can use the <img> tag to display images and embed videos or other media using appropriate HTML tags.

6. Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7. Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

## CODE:

### HTML CODE:
```
<!DOCTYPE html>
<html>
<head>
	<title>My Portfolio</title>
    <link rel="stylesheet" href="resu.css">
  </head>
<body>
	<table id="header" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#ef8812">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>
						<td>
							<font face="Comic sans MS" size="6">
								<b>My Portfolio</b>
							</font>
						</td>
						<td width="15%">
						</td>
						<td>
							<a href="#home" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Home
								</font></a></td>
						<td>
							|
						</td>
						<td>
							<a href="#about" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									About
								</font></a></td><td>
							|
						</td>
						<td>
							<a href="#projects" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Projects
							</font></a>	</td>
						<td>
							|
						</td>
						<td>
							<a href="#achievements" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Achievements
								</font></a></td>
						<td>
							|
						</td>
						<td>
							<a href="#contact" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Contact
								</font></a></td></tr></table></td></tr></table>
	<!--Header(end)-->
	<table class="t1" id="home"
		cellpadding="20" cellspacing="0" >  
		<tr><td>
				<table class = "t2" cellpadding="15" cellspacing="0" align="center">
					<tr><td align="center" valign="middle">
							<h3 class="name">
									Hello ,I am Sangeetha
							</h3><h2>
								<font face="Verdana" size="5" color="#c2c0c3">
									Student in SEC
								</font></h2></td></tr></table>	</td></tr>	</table>
	<table id="about" class="about" cellpadding="0" cellspacing="0" >
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td  align="center" class="aboutmef"
							valign="middle" colspan="2">
								About Me
							<hr color="#6eef12" width="90">
						</td>	</tr>
					<tr>
						<td width="40%">
							<img src="My.jpg">
						</td>
						<td width="60%">
							<font face="Verdana" size="4"color="white">						
								<hr color="black">
                                <p>Hi, I am Sangeetha, a passionate student and aspiring web developer. 
                                    I am currently pursuing a degree in Artificial Intelligence and Data science,2<sup>nd</sup>year in Saveetha Engineering College and have a keen interest in front-end development. 
                                    I am always eager to learn new things and take on new challenges.</p>
							 she loves to solve programming problems
								in most efficient ways. Apart from
								I has worked with
								DE Shaw and Co. as a software
								developer and IT Noida as an
								assistant professor.
							
								I do my work mainly in C-Language,
								C++ and JAVA. C++ and Data Structure
								& Algorithm are my stronger section.
								Besides these I know Web Development,
								LINUX and database as well.
								<hr color="black">

								This website is basically one of my
								Web Development project which is
								built using HTML only.
								Here one can also find ideas for
								projects in different languages.

								Thanks again for reading this,
								because of people like you, it
								exists and prospers!
								<hr color="black">
								<br>
								
							</font></td></tr></table>
				<hr color="black">
				<hr color="black">
				<hr color="black">
			</td></tr></table>
	<table id="projects" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#c2c0c3">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="black">
								Projects
							</font>
							<hr color="black" width="90">
						</td>	</tr>
					<tr>
						<td class="skills">
								<ul>
                                            <li>C Programming</li>   
                                            <li>Python</li> 
                                            <li>HTML</li>
                                            <li>Data Science</li>
                                            <li>Machine Learning</li>    
                                            <li>Website development</li>
                                            <li>IOT</li>
                                            <li>Product Development</li>
                                            <li>3D Designing</li>
                                            <li>AR Filter Developing</li>
                                            <li>Communication skills</li>
                                            <li>Image processing Techniques</li>	 
                                        </ul>
						<td width="45%">
							<img src="download.jpg" alt="Project" width="75%">
						</td></tr>	</table></td></tr>
	</table>
	<table id="achievements" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center" valign="middle">
							<font face="Verdana" size="7" color="#ef8812">
								Achievements
								<hr color="#6eef12" width="100">
							</font></td></tr><tr><td>
							<font face="Verdana" size="4" color="white"><ul><li>
										<b>Intern at Monolith</b>
										<ul><li>
												january,2023 - Present.
											</li>
								      <li>
                                                During my internship at Monolith Company, I worked on Augumented Reality 
                                                Filter using AR softwares and also learned some web AR codings
											</li></ul></li>
									<li>
										<hr color="black">
										<hr color="black">
										<hr color="black">
										<b>Microsoft Learn Student Ambassador.</b>
										<ul>
											<li>
												August,2022 - Present.
											</li>
											<li>
												Conducted events and workshops on
												different technologies.
											</li>
										</ul></li>
									<li>
										<hr color="black">
										<hr color="black">
										<hr color="black">
										<b> HackTX.</b>
										<ul><li>
												October,2021.
											</li>
											<li>
												Selected from Microsoft as Student
												ambassador where I mentored students
												in their projects.
											</li>
											<hr color="black">
										</ul>	</li></ul>
							</font></td></tr></table></td>	</tr>
	</table>
	<table id="contact" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#c2c0c3">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center"><tr><td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="black">
								Contact
							</font>
							<hr color="black" width="90">
						</td></tr><tr>
						<td align="center" valign="top">
							<table border="0" width="50%" cellpadding="15"
								cellspacing="0" align="center" bgcolor="black">
								<tr>
									<td width="30%">
										<hr color="black">
										<font face="Verdana" size="4"
											color="#ffffff">
											Name
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="text" size="40">
										</font></td>	</tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="#ffffff">
											Email
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="email" size="40">
										</font></td>	</tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="#ffffff">
											Number
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="number" size="12">
										</font></td></tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="#ffffff">
											Message
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<textarea rows="5"
												cols="37">
											</textarea>	</font></td>	</tr>
								<tr>
									<td width="30%">
									</td>
									<td width="70%">
										<button type="Submit">
											<font face="Verdana"
												size="4" color="black">
												<b>Submit</b>
											</font>
										</button>
										<hr color="black">
										<hr color="black">
									</td></tr>
							</table></td></tr>
				</table>
			</td></tr></table>
	
	<table id="footer" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#e9ac50">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>

						<td width="13%" valign="top">
							<a href="https://github.com/sangeethak15-AI" style="text-decoration:none">
								<b>GitHub</b>
							</a></td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<a href="" style="text-decoration:none">
								<b>Snapchat</b>
							</a></td>
						<td>
							|
						</td>
						<td width="13%"  valign="top">
							<a  href="https://instagram.com/_.sangiii._?igshid=NTc4MTIwNjQ2YQ==" style="text-decoration:none">
							<b>Instagram</b>	
							</a>	</td>
						<td>
							|
						</td>
						<td width="13%"  valign="top">
							<a href="#sangeethak494@gmail.com" style="text-decoration:none">
								<b>Email</b>
							</a></td>
						<td>
							|
						</td>
					</tr></table></td></tr></table>
	<table id="footer" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>
						<td width="80%" valign="top">
							<font face="Verdana"
								color="#e49620" size="5">
								©Copyright 2023 by studentportfolio.
								All rights reserved.
							</font></td></tr></table></td></tr></table></body>
</html>
```
### CSS CODE:
```
img{
    width: 100%;
    height: 1000%;
  }
  .t1{
    order:1; 
    width:100%;
      background-color: black;
  }
  .t2{
    width:90%; 
    border:0cm; 
  }
  .name{
    font-family: 'Times New Roman', Times, serif;
    font-size:40px;
     color:#ffffff;
  }
  .about{
    background-color:black;
    border:0%;
   width:100%;
   
  }
  .aboutmef{
    height:180%; 
    font-family:Verdana;
   font-size:50px;
    color:#ef8812;
  }
  .skills{
    height:10%;
    font-family:Times New Roman;
      font-size:40px;
       color:black; 
  }
  li{
    padding-top: 8%;
  }
  
```
## OUTPUT:
![Screenshot 2023-06-11 195054](https://github.com/sangeethak15-AI/Exp-1-To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/93992063/e0724fc0-d2ac-4461-907e-6acc20825bf8)
![Screenshot (1132)](https://github.com/sangeethak15-AI/Exp-1-To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/93992063/7884883b-ac6a-4eee-9758-58c50a8bc15d)
![Screenshot (1134)](https://github.com/sangeethak15-AI/Exp-1-To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/93992063/d6d56d91-e9e4-4fb1-94ce-21165da27c09)

![Screenshot (1135)](https://github.com/sangeethak15-AI/Exp-1-To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/93992063/4c1008e9-93a2-4a26-8c81-a3455f38a0b7)
![Screenshot (1133)](https://github.com/sangeethak15-AI/Exp-1-To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/93992063/9f4aa7f8-7672-451d-a6d4-3ad74617ce33)





## RESULT:
Thus, a Portfolio is created using HTML and CSS.
