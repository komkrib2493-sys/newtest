<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<title>My Monitoring Dashboard</title>

<style>

body{
margin:0;
font-family:Arial;
background:#0b132b;
color:white;
}

header{
background:#1c2541;
padding:20px;
text-align:center;
font-size:24px;
}

.dashboard{
display:grid;
grid-template-columns:1fr 1fr;
gap:20px;
padding:20px;
}

.card{
background:#1c2541;
border-radius:10px;
padding:10px;
}

iframe{
width:100%;
height:320px;
border:none;
}

</style>

</head>

<body>

<header>
My Data Dashboard
</header>

<div class="dashboard">

<div class="card">
<h3>Sensor 1</h3>
<iframe src="http://YOUR-GRAFANA-IP:3000/d-solo/UID/dashboard?panelId=1"></iframe>
</div>

<div class="card">
<h3>Sensor 2</h3>
<iframe src="http://YOUR-GRAFANA-IP:3000/d-solo/UID/dashboard?panelId=2"></iframe>
</div>

<div class="card">
<h3>Sensor 3</h3>
<iframe src="http://YOUR-GRAFANA-IP:3000/d-solo/UID/dashboard?panelId=3"></iframe>
</div>

<div class="card">
<h3>Sensor 4</h3>
<iframe src="[https://leerier-alivia-higher.ngrok-free.dev/public-dashboards/fc945f99a71d4e718d71bd475ffa3cdc]"></iframe>
</div>

</div>

</body>
</html># newtest
