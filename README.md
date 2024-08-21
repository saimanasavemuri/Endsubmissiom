body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f0ebe1; /* Light beige */
    color: #2c3e50; /* Charcoal blue */
    scroll-behavior: smooth;
}

header {
    position: relative;
    text-align: center;
    color: white;
}

.hero {
    background-image: url('https://images.unsplash.com/photo-1547658719-da2b511691e5');
    background-size: cover;
    background-position: center;
    padding: 100px 20px;
    margin-bottom: 30px;
    color: white;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
    text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

.hero .btn {
    background-color: #ecf0f1;
    color: #2c3e50;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.hero .btn:hover {
    background-color: #bdc3c7;
    transform: scale(1.05);
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

nav ul li a {
    color: #2c3e50; /* Charcoal blue */
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #16a085; /* Turquoise */
}

section {
    margin: 2rem auto;
    padding: 1rem;
    max-width: 800px;
    background-color: #ffffff; /* White */
    box-shadow: 0 0 10px rgba(44, 62, 80, 0.2); /* Charcoal blue shadow */
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 1s ease-out, transform 1s ease-out;
}

section.fade-in {
    opacity: 1;
    transform: translateY(0);
}

h2 {
    color: #34495e; /* Darker blue */
    text-align: center;
    margin-bottom: 20px;
    position: relative;
}

h2::after {
    content: '';
    display: block;
    width: 50px;
    height: 3px;
    background-color: #16a085; /* Turquoise */
    margin: 10px auto;
    border-radius: 5px;
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.project-card {
    background-color: #e5dcc1; /* Warm beige */
    padding: 1rem;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 15px rgba(44, 62, 80, 0.2); /* Charcoal blue shadow */
}

.project-card h3 {
    margin-top: 0;
    color: #2c3e50; /* Charcoal blue */
}

.project-card a {
    text-decoration: none;
    color: #16a085; /* Turquoise */
    font-weight: bold;
    transition: color 0.3s ease;
}

.project-card a:hover {
    color: #2c3e50; /* Charcoal blue */
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

form input, form textarea {
    padding: 10px;
    border: 1px solid #bdc3c7;
    border-radius: 5px;
    font-family: inherit;
    font-size: 1rem;
    resize: none;
}

form button {
    background-color: #16a085; /* Turquoise */
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

form button:hover {
    background-color: #149174; /* Darker turquoise */
    transform: scale(1.05);
}

footer {
    background-color: #2c3e50; /* Charcoal blue */
    color: #ecf0f1; /* Light ivory */
    text-align: center;
    padding: 1rem 0;
    position: relative;
    bottom: 0;
    width: 100%;
}
