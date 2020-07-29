### Hi there 👋

<!--
**dinesh99639/dinesh99639** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


<!DOCTYPE html>
<html>
<head>
	<title>Dinesh Somaraju</title>
	<link rel="icon" href="https://avatars2.githubusercontent.com/u/48937982?v=4" style="border-radius: 50%" type="image/x-icon"/>
	<!-- <meta name="viewport" content="width=device-width, initial-scale=1"> -->

	<!-- jQuery 3.5.1 -->
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css"/> -->

	<!-- BootStrap 3.4.1 -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
	
	<style type="text/css">
		*
		{
			font-size: 20px;
			line-height: 1.15;
			font-family: Times New Roman;
		}
		body
		{
			margin: 0;
		}
		.head
		{
			position: absolute;
			/*background-color: rgba(165, 55, 253, 1);*/
			background-image: linear-gradient(to right, rgb(109, 23, 203), rgb(40, 118, 249));
			width: 100%;
			height: 200px;
			z-index: -100;
		}
		.image_holder
		{
			position: relative;
			width: 100%;
			text-align: center;
			/*left: 15%;*/
			margin-top: 125px;
		}
		.pimage img
		{
			height: 150px;
			width: 150px;
			border-radius: 50%;
			margin: 0 auto;
			/*background: url(profile.jfif);*/
			background-color: rgba(0,0,0,0.5);
			transform: scale(1,1);
		}
		.pimage .name
		{
			position: absolute;
			width: 100%;
			text-align: center;
			margin-top: -40px;
			font-size: 25px;
			color: rgba(255, 255, 255, 0.95);
		}
		.icons
		{
			position: absolute;
			/*z-index: -1;*/
			top: 210px;
			height: 40px;
			width: 100%;
		}
		.icons .icon-item img
		{
			height: 40px;
			width: 40px;
		}
		.icons .icon_left
		{
			float: right;
			margin-left: 15px;
  			transition: 0.3s;
		}
		.icons .icon_right
		{
			float: left;
			margin-right: 15px;
  			transition: 0.2s;
		}
		.icon_left:hover, .icon_right:hover
		{
			margin-top: 5px;
		}



		.body
		{
			position: absolute;
			width: 100%;
			top: 320px;
		}

		.projects .title
		{
			text-align: center;
			font-size: 30px;
			margin-bottom: 20px;
		}
		.projects .sidebar
		{
			margin-left: 0;
			border: 1px solid rgba(0, 0, 0, 0.3);
			border-radius: 3px;
			text-align: center;
		}
		.sidebar .title
		{
			height: 40px;
			padding-top: 7px;
			font-size: 20px;
			background-image: linear-gradient(to right, rgb(109, 23, 203), rgb(40, 118, 249));
			color: rgba(255, 255, 255, 0.95);
		}
		.sidebar-list ul
		{
			padding: 0;
		}
		.sidebar-list li
		{
			list-style: none;
			text-align: center;
			margin-bottom: 7px;
		}

		.project
		{
			/*border: 1px solid rgba(0, 0, 0, 0.3);*/
			border-radius: 3px;
			box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
			margin-bottom: 30px;
		}
		.project .name
		{
			padding-top: 10px;
			padding-left: 20px;
			font-size: 25px;
			font-weight: bold;
			color: rgba(0, 0, 0, 0.8);
		}
		.project .name a
		{
			text-decoration: none;
		}
		.project .full_name
		{
			padding-top: 2px;
			padding-left: 20px;
			font-size: 15px;
			color: rgba(0, 0, 0, 0.6);
		}
		.project .desc
		{
			font-size: 17px;
			padding: 10px 20px 20px 20px;
			text-align: justify;
		}
		.project .desc_title
		{
			font-size: 17px;
			padding: 10px 20px 0px 20px;
			text-align: justify;
			font-weight: bold;
		}
		.project .col-sm-2 .project_icon
		{
			object-fit: cover;
			width: 100%;
			/*transform: translate(50%, 50%);*/
		}
		.project .tech-tag
		{
			background-color: rgba(0, 0, 0, 0.3);
			display: inline-block;
			border-radius: 10px;
			font-size: 18px;
			padding: 0 8px;
			margin-right: 10px;


			/*background-color: #8000FF; //Violet
			color: white;*/

			/*background-color: #02B30E; //Green
			color: white;*/

			/*background-color: #0089E4; //Blue
			color: white;*/

			/*background-color: #FFA200; //Orange
			color: white;*/

			/*background-color: #00CDB8; //Darkblue
			color: white;*/

			/*background-color: #FF00C4; //pink
			color: white;*/

			/*background-color: #800000; //maroon
			color: white;*/
		}
		.project .download
		{
			width: 35px;
		}





		.footer
		{
			position: absolute;
			bottom: 0;
			/*background-color: rgb(53, 54, 58);*/
			background-image: linear-gradient(to right, rgb(109, 23, 203), rgb(40, 118, 249));
			color: rgba(255, 255, 255, 0.95);
			width: 100%;
			padding-top: 3px;
			height: 20px;
			text-align: center;
		}
		.footer .desc
		{
			font-size: 15px;
		}


		@media only screen and (max-width: 590px)
		{
			.icons
			{
				margin-top: 60px;
			}
			.icon_left, .icon_right
			{

			}
			.icons .col-sm-2
			{
				width: 0px;
			}
		}

	</style>

</head>
<body>
	<div class="head">
		<div class="image_holder">
			<div class="pimage">
				<div class="name">Dinesh Somaraju</div>
				<img src="https://avatars2.githubusercontent.com/u/48937982?v=4">
			</div>
		</div>
		<div class="icons">
			<div class="container">
				<div class="row">
					<!-- <div class="col-sm-1"></div> -->
					<div class="col-sm-5">
						<div class="icon-item icon_left"><a target="_blank" id="facebook"><img src="icons/facebook.png"></a></div>
						<div class="icon-item icon_left"><a target="_blank" id="instagram"><img src="icons/instagram.png"></a></div>
						<div class="icon-item icon_left"><a target="_blank" id="linkedin"><img src="icons/linkedin.png"></a></div>
						<div class="icon-item icon_left"><a target="_blank" id="twitter"><img src="icons/twitter.png"></a></div>
					</div>
					<div class="col-sm-2"></div>
					<div class="col-sm-5">
						<div class="icon-item icon_right"><a target="_blank" id="gmail"><img src="icons/gmail.png"></a></div>
						<div class="icon-item icon_right"><a target="_blank" id="github"><img src="icons/github.png"></a></div>
						<div class="icon-item icon_right"><a target="_blank" id="stackoverflow"><img src="icons/stackoverflow.png"></a></div>
						<div class="icon-item icon_right"><a target="_blank" id="whatsapp"><img src="icons/whatsapp.png"></a></div>
					</div>
					<!-- <div class="col-sm-1"></div> -->
				</div>
			</div>
		</div>
	</div>
	
	<div class="body">
		<div class="projects">
			<div class="title">Projects</div>
			<div class="container-fluid">
				<div class="row">
					<div class="col-sm-3" style="padding-left: 0;">
						<div class="sidebar">
							<div class="title">Technologies</div>
							<div class="sidebar-list">
								<ul>
									<li>HTML</li>
									<li>CSS</li>
									<li>JavaScript</li>
									<li>jQuery</li>
									<li>BootStrap</li>
									<li>PHP</li>
									<li>MySQL</li>
									<li>C</li>
									<li>C++</li>
									<li>Java</li>
									<li>Python</li>
								</ul>
							</div>
						</div>
					</div>
					<div class="col-sm-9">
						<div class="projects_list">

							
							<!-- <div class="project">
								<div class="row">
									<div class="col-sm-2">
										<img class="project_icon" src="icons/github.png">
									</div>
									<div class="col-sm-10">
										<div class="name">Project Name</div>
										<div class="full_name">@fullname</div>
										<div class="desc_title">Project Description:</div>
										<div class="desc">This project is to make sure the password is not revealed during the entry of password by the user. Whenever the user tries to enter the password for some login purpose, it is more prone to being noticed by others who may use it for wrong deeds.</div>
										<div class="row">
											<div class="col-sm-10" style="padding-left: 35px;">
												<div style="background-color: #8000FF;color: white;" class="tech-tag">JavaScript</div>
												<div class="tech-tag">HTML</div>
											</div>
											<div class="col-sm-2">
												<a style="float: right; padding: 0 10px 1px 0;" href="https://github.com/dinesh99639/colorhunt/archive/master.zip">
													<svg style="width: 30px; height: 30px;" viewBox="0 0 490.4 490.4">
														<path d="M490.4,245.2C490.4,110,380.4,0,245.2,0S0,110,0,245.2s110,245.2,245.2,245.2S490.4,380.4,490.4,245.2z M24.5,245.2 c0-121.7,99-220.7,220.7-220.7s220.7,99,220.7,220.7s-99,220.7-220.7,220.7S24.5,366.9,24.5,245.2z"/>
														<path d="M253.9,360.4l68.9-68.9c4.8-4.8,4.8-12.5,0-17.3s-12.5-4.8-17.3,0l-48,48V138.7c0-6.8-5.5-12.3-12.3-12.3 s-12.3,5.5-12.3,12.3v183.4l-48-48c-4.8-4.8-12.5-4.8-17.3,0s-4.8,12.5,0,17.3l68.9,68.9c2.4,2.4,5.5,3.6,8.7,3.6 S251.5,362.8,253.9,360.4z"/>
													</svg>
												</a>
											</div>
										</div>
									</div>
								</div>
							</div> -->


						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- <div class="footer"><div class="desc">Copyright&#xa9; Dinesh Somaraju</div></div> -->
</body>
</html>

<script>
	var guser =  "dinesh99639";
	var bg_colors = ['#8000FF', '#02B30E', '#0089E4', '#FFA200', '#00CDB8', '#FF00C4'];

	$(document).ready(()=>{

		$.ajax({
			url: "user_info.json",
			success: function (data) {
				$('#twitter').attr("href", data.twitter);
				$('#linkedin').attr("href", data.linkedin);
				$('#instagram').attr("href", data.instagram);
				$('#facebook').attr("href", data.facebook);
				$('#gmail').attr("href", "mailto:"+data.email);
				$('#github').attr("href", data.github);
				$('#stackoverflow').attr("href", data.stackoverflow);
				$('#whatsapp').attr("href", data.whatsapp);

			}
		});


		// projects = [];
		
		$.ajax({
			url: "https://api.github.com/users/"+guser+"/repos",
			success: function (data) {
				n = data.length;
				for (i=0; i<n; i++)
				{
					// console.log(data[i].name);

					project_info = '';
					$.ajax({
						async: false,
						url: 'https://raw.githubusercontent.com/'+data[i].full_name+'/master/project_info.json',
						success: function (project_info_data) {
							project_info = JSON.parse(project_info_data);

							tags_html = '';

							for (j=0; j<project_info.tech.length; j++)
							{
								color = bg_colors[Math.floor(Math.random() * bg_colors.length)];
								tags_html += '<div style="background-color: '+color+';color: white;" class="tech-tag">'+project_info.tech[j]+'</div>'
							}

							project_div = '<div class="project"><div class="row"><div class="col-sm-2"><img class="project_icon" src="icons/github.png"></div><div class="col-sm-10"><div class="name"><a href="https://github.com/'+data[i].full_name+'" target="_blank">'+project_info.name+'</a></div><div class="full_name">@'+data[i].full_name+'</div><div class="desc_title">Project Description:</div><div class="desc">'+project_info.desc+'</div><div class="row"><div class="col-sm-10" style="padding-left: 35px;">'+tags_html+'</div><div class="col-sm-2"><a style="float: right; padding: 0 10px 1px 0;" href="https://github.com/dinesh99639/colorhunt/archive/master.zip"><svg style="width: 30px; height: 30px;" viewBox="0 0 490.4 490.4"><path d="M490.4,245.2C490.4,110,380.4,0,245.2,0S0,110,0,245.2s110,245.2,245.2,245.2S490.4,380.4,490.4,245.2z M24.5,245.2 c0-121.7,99-220.7,220.7-220.7s220.7,99,220.7,220.7s-99,220.7-220.7,220.7S24.5,366.9,24.5,245.2z"/><path d="M253.9,360.4l68.9-68.9c4.8-4.8,4.8-12.5,0-17.3s-12.5-4.8-17.3,0l-48,48V138.7c0-6.8-5.5-12.3-12.3-12.3 s-12.3,5.5-12.3,12.3v183.4l-48-48c-4.8-4.8-12.5-4.8-17.3,0s-4.8,12.5,0,17.3l68.9,68.9c2.4,2.4,5.5,3.6,8.7,3.6 S251.5,362.8,253.9,360.4z"/></svg></a></div></div></div></div></div>';

							$('.projects_list').append(project_div);
						},
						error: function(){
							project_div = '<div class="project"><div class="row"><div class="col-sm-2"><img class="project_icon" src="icons/github.png"></div><div class="col-sm-10"><div class="name"><a href="https://github.com/'+data[i].full_name+'" target="_blank">'+data[i].name+'</a></div><div class="full_name">@'+data[i].full_name+'</div><div class="desc_title">Project Description:</div><div class="desc">No description provided by the user</div><div class="row"><div class="col-sm-10" style="padding-left: 35px;"></div><div class="col-sm-2"><a style="float: right; padding: 0 10px 1px 0;" href="https://github.com/'+data[i].full_name+'/archive/master.zip"><svg style="width: 30px; height: 30px;" viewBox="0 0 490.4 490.4"><path d="M490.4,245.2C490.4,110,380.4,0,245.2,0S0,110,0,245.2s110,245.2,245.2,245.2S490.4,380.4,490.4,245.2z M24.5,245.2 c0-121.7,99-220.7,220.7-220.7s220.7,99,220.7,220.7s-99,220.7-220.7,220.7S24.5,366.9,24.5,245.2z"/><path d="M253.9,360.4l68.9-68.9c4.8-4.8,4.8-12.5,0-17.3s-12.5-4.8-17.3,0l-48,48V138.7c0-6.8-5.5-12.3-12.3-12.3 s-12.3,5.5-12.3,12.3v183.4l-48-48c-4.8-4.8-12.5-4.8-17.3,0s-4.8,12.5,0,17.3l68.9,68.9c2.4,2.4,5.5,3.6,8.7,3.6 S251.5,362.8,253.9,360.4z"/></svg></a></div></div></div></div></div>';

							$('.projects_list').append(project_div);
						}
					});

					// $('.projects_list').append(data[i].name+"<br>");
					// project_div = '<div class="project"><div class="row"><div class="col-sm-2"><img class="project_icon" src="icons/github.png"></div><div class="col-sm-10"><div class="name">Project Name</div><div class="full_name">@fullname</div><div class="desc_title">Project Description:</div><div class="desc">This project is to make sure the password is not revealed during the entry of password by the user. Whenever the user tries to enter the password for some login purpose, it is more prone to being noticed by others who may use it for wrong deeds.</div><div class="row"><div class="col-sm-10" style="padding-left: 35px;"><div class="tech-tag">JavaScript</div><div class="tech-tag">HTML</div></div><div class="col-sm-2"><a style="float: right; padding: 0 10px 1px 0;" href="https://github.com/dinesh99639/colorhunt/archive/master.zip"><img class="download" src="icons/download.png"></a></div></div></div></div></div>';

					// $('.projects_list').append(project_div);
				}
				// console.log("\nRepos : "+data.length);
				// console.log(data);
			}
		});
	});
	
</script>
