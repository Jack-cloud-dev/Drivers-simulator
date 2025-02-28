body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f4f4f4;
}

header {
    background: #222;
    color: white;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

nav ul li {
    margin: 10px;
}

nav a {
    text-decoration: none;
    color: #007BFF;
    font-size: 18px;
    padding: 10px;
    display: block;
}

section {
    padding: 20px;
    max-width: 600px;
    margin: auto;
}

form {
    display: flex;
    flex-direction: column;
    width: 90%;
    max-width: 300px;
    margin: auto;
}

input, textarea, button {
    margin: 5px 0;
    padding: 12px;
    font-size: 16px;
}

button {
    background: #007BFF;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background: #0056b3;
}

footer {
    background: #222;
    color: white;
    padding: 10px;
    margin-top: 20px;
}

/* Adattamenti per telefoni */
@media (max-width: 600px) {
    nav ul {
        flex-direction: column;
        align-items: center;
    }

    nav a {
        font-size: 16px;
    }

    section {
        padding: 15px;
    }
}# Drivers-simulator
