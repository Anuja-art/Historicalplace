<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Historical Places in India</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #451957;
            color: white;
            padding: 20px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }
        section {
            display: none;
            padding: 50px 20px;
            text-align: center;
        }
        section.active {
            display: block;
        }
        .places-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .place-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            width: calc(30% - 40px);
            min-width: 250px;
            text-align: left;
        }
        .place-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .place-card h3 {
            color: #451957;
            padding: 10px;
        }
        .place-card p {
            padding: 0 10px 10px;
        }
        .place-card a {
            display: block;
            text-align: center;
            color: white;
            background-color: #451957;
            padding: 10px;
            text-decoration: none;
            border-radius: 0 0 10px 10px;
        }
    </style>

<script>
    function showPage(pageId) {
    var pages = document.querySelectorAll('section');
    pages.forEach(page => page.style.display = 'none'); // Hide all sections
    document.getElementById(pageId).style.display = 'block'; // Show the selected page
}

    window.onload = function() {
        showPage('home');
    }
</script>

</head>

<body>
    <header>
        <h1>Historical Places in India</h1>
        <nav>
            <ul>
                <li><a onclick="showPage('home')">Home</a></li>
                <li><a onclick="showPage('places')">Places</a></li>
                <li><a onclick="showPage('map')">Map</a></li>
                <li><a onclick="showPage('about')">About</a></li>
                <li><a onclick="showPage('contact')">Contact</a></li>
            </ul>
        </nav>
        
    </header>

    <section id="home" class="active">
        
        <h2>Welcome to Incredible India</h2>
        <p>Discover the rich cultural heritage of India.</p>
    </section>
    <section id="map">
        <h2>Map of India</h2>
        <div class="map-container">
            <iframe id="googlemap" 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5027208.243378985!2d74.02475943768645!3d20.593683079246188!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjDCsDM1JzM2LjkiTiA3OMKwNTcnNTcuOSJF!5e0!3m2!1sen!2sin!4v1643113510863!5m2!1sen!2sin" 
                allowfullscreen="" 
                loading="lazy">
            </iframe>
        </div>
    </section>
    <style>
    .map-container {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 80vh;
       
        margin: 0 auto;
    }
    #googlemap {
        width: 90vw;
        max-width: 900px;
        height: 80vh;
        border: none;
    }
    body { /*backgroung*/
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    min-height: 100vh; /* Ensures full-page coverage */
    background: url('backgroundpic.jpeg') no-repeat center center fixed ;
    background-size: cover; /* Covers entire screen without distortion */
    color: white;
    display: flex;
    flex-direction: column;
}

    </style>
  

    <section id="places">
        <h2>Historical Places</h2>
        <div class="places-grid">
            <div class="place-card">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Taj_Mahal_%28Edited%29.jpeg/250px-Taj_Mahal_%28Edited%29.jpeg" alt="Taj Mahal">
<h3>Taj Mahal</h3>
<p>Agra, Uttar Pradesh</p>
<a href="https://en.wikipedia.org/wiki/Taj_Mahal" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="qutub.jpeg">
<h3>Qutub Minar</h3>
<p>Delhi</p>
<a href="https://en.wikipedia.org/wiki/Qutub_Minar" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Victoria_Memorial_situated_in_Kolkata.jpg/300px-Victoria_Memorial_situated_in_Kolkata.jpg" alt="Victoria Memorial">
<h3>Victoria Memorial</h3>
<p>Kolkata, West Bengal</p>
<a href="https://en.wikipedia.org/wiki/Victoria_Memorial%2C_Kolkata" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="charminar.jpeg" alt="Charminar">
<h3>Charminar</h3>
<p>Hyderabad, Telangana</p>
<a href="https://en.wikipedia.org/wiki/Charminar" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="https://media.istockphoto.com/id/535570117/photo/golden-temple-in-amritsar-punjab-india.jpg?s=612x612&w=0&k=20&c=TAgZK64Qz6YsljOK1rXZrrW1u1YSlb9e_YBEmm2pfBw=" alt="Golden Temple">
<h3>Golden Temple</h3>
<p>Amritsar, Punjab</p>
<a href="https://en.wikipedia.org/wiki/Golden_Temple" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="redfort.jpeg" alt="Red Fort">
<h3>Red Fort</h3>
<p>Delhi</p>
<a href="https://en.wikipedia.org/wiki/Red_Fort" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Jodhpur_mehrangarh_fort.jpg/250px-Jodhpur_mehrangarh_fort.jpg" alt="Mehrangarh Fort">
<h3>Mehrangarh Fort</h3>
<p>Jodhpur, Rajasthan</p>
<a href="https://en.wikipedia.org/wiki/Mehrangarh" target="_blank">See More</a>
</div>
<div class="place-card">
<img src="suntemple.jpeg" alt="Konark Sun Temple">
<h3>Konark Sun Temple</h3>
<p>Konark, Odisha</p>
<a href="https://en.wikipedia.org/wiki/Konark_Sun_Temple" target="_blank">See More</a>
</div>
            <div class="place-card">
                <img src="qutub.jpeg" alt="Qutub Minar">
                <h3>Qutub Minar</h3>
                <p>Delhi</p>
                <a href="https://en.wikipedia.org/wiki/Qutub_Minar" target="_blank">See More</a>
            </div>
            <!-- Add more place-cards similarly -->
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <div class="about-container">
            <p>Welcome to our website, where we explore the rich history of India's most remarkable places. 
               Our mission is to bring history closer to you by sharing insightful details about the heritage sites across India.</p>
    
            <p>India is home to countless architectural wonders, cultural landmarks, and timeless monuments. 
               Whether you're a history enthusiast, traveler, or student, this site will help you discover the beauty and significance of these locations.</p>
        </div>
    </section>
    
    
    <section id="contact">
        <h2>Contact Us</h2>
        <div>
            <table>
                <tr>
                    <td><label for="name">Name:</label></td>
                    <td><input type="text" id="name" name="name" required></td>
                </tr>
                <tr>
                    <td><label for="email">Email:</label></td>
                    <td><input type="email" id="email" name="email" required></td>
                </tr>
                <tr>
                    <td><label for="issue">Issue:</label></td>
                    <td><input type="text" id="issue" name="issue" required></td>
                </tr>
                <tr>
                    <td><label for="description">Description:</label></td>
                    <td><textarea id="description" name="description" rows="3" required></textarea></td>
                </tr>
                <tr>
                    <td colspan="2"><button type="submit">Send</button></td>
                </tr>
            </table>
        </div>
    </section>
    
    
    <style>
       #contact {
    display: none;
    text-align: center;
    position: relative;
    height: 100vh;
}

#contact div {
    width: 600px; /* Increased width for longer horizontal size */
    background: rgba(0, 0, 0, 0.6); /* Keeps the dark box effect */
    padding: 20px;
    border-radius: 10px;
    color: white;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: auto;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

table {
    width: 100%; /* Ensures table takes full width of the div */
}

td {
    padding: 10px;
}

input, textarea {
    width: 100%; /* Ensures input fields expand */
    padding: 8px;
    border-radius: 5px;
    border: none;
}

        label {
            color: white; /* Ensures labels (Name, Email, Issue, Description) are clearly visible */
            font-weight: bold;
            font-size: 16px;
        }
    
        input, textarea {
    width: 100%; /* Ensures input fields expand */
    padding: 8px;
    border-radius: 5px;
    border: none;
}
    
        input:focus, textarea:focus {
            outline: 2px solid #451957; /* Highlight focus */
        }
    
        button {
            width: 100%;
            padding: 10px;
            background: #451957; /* Matches header color */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
    
        button:hover {
            background: #730f30; /* Slightly darker on hover */
        }
    </style>
    
</style>
</body>
</html>
