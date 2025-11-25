# Sigma
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Mi Marca de Ropa</title>
<style>
body {
margin: 0;
font-family: Arial, sans-serif;
background: #f5f5f5;
color: #222;
}
header {
background: #000;
color: white;
padding: 20px;
text-align: center;
}
nav a {
color: white;
margin: 0 15px;
text-decoration: none;
font-weight: bold;
}
.hero {
height: 80vh;
background: url('https://via.placeholder.com/1200x800') center/cover;
display: flex;
align-items: center;
justify-content: center;
text-align: center;
color: white;
}
.hero h1 {
font-size: 3rem;
background: rgba(0,0,0,0.5);
padding: 20px;
border-radius: 10px;
}
.section {
padding: 40px 20px;
text-align: center;
}
.productos {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 20px;
padding: 20px;
}
.card {
background: white;
padding: 15px;
border-radius: 10px;
box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}
.card img {
width: 100%;
border-radius: 10px;
}
footer {
background: #000;
color: white;
text-align: center;
