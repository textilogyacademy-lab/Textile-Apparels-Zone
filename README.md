
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f9f9f9;
    color: #333;
}

/* Navigation */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    background: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
    z-index: 100;
}

nav .logo {
    font-size: 24px;
    font-weight: bold;
    color: #d63384; /* Floral Pink Theme */
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
}

/* Hero Section */
header {
    height: 80vh;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('hero-bg.jpg'); /* Add a floral image here */
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.hero-content h1 {
    font-size: 48px;
    margin-bottom: 10px;
}

.btn {
    display: inline-block;
    padding: 10px 25px;
    background: #d63384;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
}

/* Services Section */
#services {
    padding: 80px 50px;
    text-align: center;
}

.service-container {
    display: flex;
    justify-content: space-around;
    margin-top: 40px;
    gap: 20px;
}

.service-box {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    flex: 1;
}

footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: white;
}
